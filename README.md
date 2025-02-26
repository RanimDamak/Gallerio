# Gallerio

Gallerio is a responsive image gallery website designed to showcase beautiful images with a clean and modern UI. It features a flexible grid layout, search functionality, and interactive image overlays, all powered by HTML and CSS.

## Features

- Responsive grid layout for the gallery.
- Image overlays with titles.
- Search bar for large screens.
- Mobile-friendly navigation.
- Interactive toolbar with options to add images and download them.

## Project Structure

```
Gallerio/
│
├── index.html               # Main HTML file
├── main.css                 # Main CSS file for styling
│
└── assets/
    ├── fontawesome/          # Font Awesome icons
    │   ├── css/
    │   │   ├── all.css
    │   │   ├── all.min.css
    │   │   ├── brands.css
    │   │   ├── brands.min.css
    │   │   ├── fontawesome.css
    │   │   ├── fontawesome.min.css
    │   │   ├── regular.css
    │   │   ├── regular.min.css
    │   │   └── solid.css
    │   │
    │   └── webfonts/         # Required font files
    │
    └── pictures/             # Images used in the gallery
        ├── camera.png
        ├── ice-mountain.jpg
        ├── river.jpg
        ├── valley.jpg
        ├── wave.jpg
        ├── flowers.jpg
        ├── rocky-river.jpg
        ├── forest.jpg
        ├── lake.jpg
        ├── hill.jpg
        ├── rocks.jpg
        └── autumn.jpg
```

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/RanimDamak/Gallerio.git
    ```
2. Open `index.html` in your preferred browser.

## Usage

- Navigate through the gallery to view images.
- Hover over images to see their titles.
- Use the search bar on large screens to filter images.
- Use the toolbar to add or download images (functionalities to be implemented).

## Technologies Used

- **HTML5**: Structure and layout of the web page.
- **CSS3**: Styling, grid layout, and responsive design.
- **Font Awesome**: Icons for search, user login, and toolbar actions.

## Responsive Design

- The layout adjusts to different screen sizes using CSS Grid and Media Queries.
- On smaller screens, the search bar is hidden, and a search icon is displayed instead.
