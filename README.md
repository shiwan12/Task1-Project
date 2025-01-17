# Task1-Project
# Scroll Reveal Animation

This project demonstrates a scroll-based animation effect where elements (`.box` class) appear and scale up as they enter the viewport while scrolling down the page. The animation is controlled using JavaScript and CSS keyframes, providing a smooth transition for elements as they become visible.

## Features
- **Scroll-based reveal**: Elements with the `.reveal` class will fade and scale into view as you scroll.
- **CSS Animations**: Each element animates using the `appear` keyframes to scale and change opacity.
- **Responsive layout**: The `.box` elements are arranged in a flexbox layout that adapts to different screen sizes.

## Files
- **index.html**: The HTML structure, which contains multiple `.box` elements with a `.reveal` class.
- **index.css**: The CSS styles that include the layout and animation for the `.box` and child elements.
- **index.js**: The JavaScript file that adds the scroll-based reveal functionality.

## Setup Instructions

1. **Clone the repository** (or download the files):
   - If using Git: 
     ```bash
     git clone <repository-url>
     ```
   - Alternatively, download the files manually.

2. **File Structure**:
   The project consists of three primary files:
   - `index.html` (HTML structure)
   - `index.css` (Styling and animations)
   - `index.js` (Scroll reveal logic)

3. **Run the Project**:
   - Open `index.html` in your browser to see the scroll-based reveal effect in action.

4. **How to Use**:
   - As you scroll down the page, elements with the `.reveal` class will animate into view.
   - You can add more `.box` elements or modify the animation in `index.css` as per your needs.

## Customization

- **Add More Boxes**:
   To add more `.box` elements, simply duplicate the existing `<div class="box reveal">` blocks in `index.html`.

- **Adjust Animation**:
   You can customize the animation by modifying the `@keyframes appear` in `index.css`. For example, change the scale values, animation duration, or opacity levels.

- **Change Colors or Layout**:
   You can update the gradient, background colors, shadows, and layout properties in `index.css` to match your design.
