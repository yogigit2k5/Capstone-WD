# Capstone-WD
# FreshFood - Food Delivery Landing Page

This is a responsive, static landing page for "FreshFood," a fictional food delivery service. This project was created as a 1st-year B.Tech CSE web development assignment.

## Project Theme
**Theme:** Food Delivery
**Goal:** To create a modern, appetizing interface that allows users to quickly view popular menu items and contact the service. The design prioritizes speed, visual appeal, and ease of use on mobile devices.

## Features
* **Semantic HTML5:** Built using proper tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` for better structure and accessibility.
* **CSS Grid & Flexbox:**
    * **Flexbox:** Used for the navigation bar, hero section alignment, and feature cards.
    * **CSS Grid:** Used for the "Popular Choices" menu section to create a responsive card layout.
* **Responsive Design:** The layout adapts seamlessly to different screen sizes (Mobile, Tablet, Desktop).
* **Animations:**
    * **Keyframes:** A smooth slide-up fade-in animation (`slideUp`) on the hero text.
    * **Transitions:** Hover effects on buttons and menu cards.
* **Contact Form:** A styled HTML form with labels and inputs for user inquiries.
* **Accessibility:** Includes a "Skip to main content" link and proper `alt` text for all images.

## Breakpoints
The CSS is designed with a "Desktop-First" approach, using `@media` queries to adapt for smaller screens:

1.  **Desktop (Default):** Full-width layouts, horizontal navigation.
2.  **Tablet (max-width: 768px):** * Navigation links are hidden (simulating a mobile menu).
    * Hero section stacks vertically (text on top, image on bottom).
3.  **Mobile (max-width: 600px):**
    * Menu Grid shifts to a single column for easy scrolling.
    * Typography sizes adjust for readability.

## How to Run
1.  Download or Clone the project repository.
2.  Ensure the folder structure includes `index.html`, `style.css`, and the `images/` folder (if using local images).
3.  Double-click `index.html` to open it in your default web browser (Chrome, Edge, Firefox, etc.).

## Technologies Used
* HTML5
* CSS3
* Google Fonts (Poppins)
* Unsplash (Stock Images)

## Credits
* **Fonts:** [Poppins by Google Fonts](https://fonts.google.com/specimen/Poppins)
* **Images:** Sourced from Unsplash.com.
