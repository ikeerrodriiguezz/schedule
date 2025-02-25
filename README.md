# Home Iker - Schedule Webpage

## Overview

This project is a simple web page that provides quick access to educational resources and displays a weekly schedule. The page features a navigation menu with links to commonly used websites and a detailed schedule table with interactive buttons.

## Features

- Navigation bar with icons linking to Gmail, Moodle, Google Calendar, Google Drive, Google Classroom, and App Inventor.
- A weekly schedule displayed in a table format.
- Each schedule slot is linked to specific resources or activities via buttons.
- The page is styled with custom CSS and includes responsive design for mobile devices.

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling and layout.
- **Fonts**: Uses 'TF2 Build' from an external CDN.
- **Media Assets**: Custom icons and background image.

## Setup

1. Clone this repository:

```bash
git clone <repository_url>
```

2. Open the `index.html` file in a web browser.

3. Make sure the `media` folder with all icons and images is in the same directory.

## HTML Structure

- `<nav>`: Contains links with icons to external resources.
- `<article>`: Displays the schedule using a `<table>` element.
- `<button>` elements: Used within the table to provide links to specific classes or activities.

## CSS Highlights

- **Responsive Design**: Media queries are used to hide elements and adjust layouts on smaller screens.
- **Button Styles**: `.BUTTON_XII` class defines the style and hover effects for schedule buttons.
- **Background and Colors**: The body has a background image, and elements use transparent and gradient backgrounds for a modern look.

## Responsive Design

The CSS includes a media query to adjust the layout for screens smaller than 900px. The menu is hidden, and the schedule takes the full width of the screen.

## License

This project is licensed under the MIT License.

## Author

[Iker](https://github.com/ikeerrodriiguezz)
