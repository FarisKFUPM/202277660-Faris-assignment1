# Technical Documentation

## Overview
This document outlines the technical implementation of the personal portfolio website.

## Architecture
The project follows a standard static website architecture:
-   **HTML5**: Provides the structure and semantic meaning of the content.
-   **CSS3**: Handles the presentation, layout (Flexbox/Grid), and theming (CSS Variables).
-   **JavaScript (ES6+)**: Manages user interaction and dynamic behavior.

### File Structure
-   `index.html`: The main entry point.
-   `css/styles.css`: Contains all stylesheets.
-   `js/script.js`: Contains all logic.
-   `assets/`: Stores static assets like images.

## Key Features Implementation

### 1. Responsive Design
-   **Media Queries**: Breakpoints are set for mobile (<768px), tablet (768px - 1024px), and desktop (>1024px).
-   **Flexbox & Grid**: Used for layout management.
    -   *Grid*: Used for the "Projects" section to create a responsive card layout.
    -   *Flexbox*: Used for the navigation bar, hero section alignment, and footer.

### 2. Dark/Light Mode
-   **CSS Variables**: Defined in `:root` for light mode and `[data-theme="dark"]` for dark mode.
-   **Persistence**: `localStorage` is used to save the user's preference.
-   **Logic**:
    1.  On load, check `localStorage` for 'theme'.
    2.  If 'dark', add `data-theme="dark"` to `<body>`.
    3.  On toggle click, switch the attribute and update `localStorage`.

### 3. Contact Form
-   **Event Listener**: Listens for the `submit` event on the form.
-   **Prevention**: `e.preventDefault()` stops the page from reloading.
-   **Feedback**: A simple `alert()` provides user feedback (since no backend is connected).

## Code Quality
-   **Semantic HTML**: Used `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
-   **Comments**: Key sections of CSS and JS are commented for better maintainability.
-   **Formatting**: Code is consistently indented (4 spaces).

## Future Improvements
-   **Backend Integration**: Connect the contact form to a service like Formspree or a custom backend.
-   **Accessibility**: Further enhance ARIA labels and keyboard navigation.
-   **Performance**: Optimize image loading (lazy loading) and minify CSS/JS for production.
