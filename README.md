# Home Iker - Schedule Webpage

## Overview

**Home Iker** is an interactive and responsive web page designed to provide easy access to educational resources and display a weekly schedule. It includes a navigation menu with quick links to various platforms, such as Gmail, Moodle, Google Calendar, Google Drive, Google Classroom, and App Inventor. The page also features a dynamic schedule, where each time slot contains clickable buttons linking to relevant courses or activities.

## Features

- **Navigation Bar**: Quick access to essential educational resources via clickable icons (Gmail, Moodle, Google Calendar, Google Drive, Google Classroom, App Inventor).
- **Interactive Schedule**: A weekly timetable displayed in a table format with clickable buttons linking to specific resources or activities.
- **Custom Styling**: Tailored CSS that gives the page a modern and sleek look, including animations and hover effects.
- **Responsive Design**: Optimized for mobile devices, adjusting the layout and hiding elements on smaller screens to ensure usability.

## Technologies Used

- **HTML**: Provides the structure for the webpage and the schedule table.
- **CSS**: Custom styles and animations for a modern, user-friendly interface.
- **Fonts**: 'TF2 Build' font, loaded from an external CDN for a unique look.
- **Media Assets**: Includes custom icons and a background image to enhance the visual experience.

## File Structure

```
/HomeIker-Schedule
│
├── /css
│   └── styles.css          # Custom styles for the webpage
│
├── /media
│   ├── gmail.png           # Gmail icon
│   ├── moodle.png          # Moodle icon
│   ├── calendar.png        # Google Calendar icon
│   ├── drive.png           # Google Drive icon
│   ├── classroom.png       # Google Classroom icon
│   ├── appinventor.png     # App Inventor icon
│   ├── background.png      # Background image for the webpage
│   └── mobile.jpg          # Mobile background image
│
└── index.html              # Main HTML file for the schedule webpage
```

## Setup

To set up the project locally:

1. **Clone the repository**:

   ```bash
   git clone <repository_url>
   ```

2. **Open the `index.html` file** in your browser to view the schedule webpage.

3. **Ensure the `media` folder** containing all icons and images is placed in the same directory as the `index.html` file for proper asset linking.

## HTML Structure

- **`<nav>`**: Contains a set of `<a>` links with icons that redirect users to external resources (Gmail, Moodle, etc.).
- **`<article>`**: Displays the weekly schedule using a `<table>` element, where each cell contains a clickable button.
- **`<button>`**: Inside table cells, these buttons link to specific resources like online courses or external platforms.

## CSS Highlights

- **Responsive Design**: The layout is adaptable, with media queries used to hide elements and adjust the table width on smaller screens (e.g., under 900px).
- **Button Styles**: The `.BUTTON_XII` class defines the button appearance, including a linear gradient background, hover effects, and smooth transitions.
- **Animations**: Buttons and images feature hover animations (scaling, glowing) for an interactive experience.
- **Modern Backgrounds and Colors**: The body has a custom background image, with elements using transparent and gradient backgrounds for a contemporary design.

## Responsive Design

The page is fully responsive, with key changes for smaller screens:

- The navigation menu (`#menu`) is hidden on screens smaller than 900px.
- The schedule table expands to fill the full width of the screen, ensuring optimal usability on mobile devices.
- Buttons scale down slightly on mobile to maintain clarity and ease of use.

## Live Demo

You can view the schedule webpage at the following link:
[**Schedule Webpage**](https://ikeerrodriiguezz.gitlab.io/schedule/)

## Author

[**Iker Rodríguez**](https://gitlab.com/ikeerrodriiguezz)
