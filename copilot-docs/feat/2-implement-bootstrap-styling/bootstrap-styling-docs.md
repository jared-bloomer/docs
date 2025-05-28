# Bootstrap Integration and Styling Documentation

## Overview
This project uses [Bootstrap 5](https://getbootstrap.com/) to provide a modern, responsive, and accessible user interface for the GitHub Pages site. The integration includes support for dark/light mode, a responsive layout, and enhanced UI components.

## Integration Steps
1. **Bootstrap CDN**: The Bootstrap CSS and JS bundles are included via CDN in the `<head>` and before the closing `</body>` tag of `index.html`.
2. **Layout Refactor**: The homepage layout uses Bootstrap's grid system, containers, and utility classes for structure and responsiveness.
3. **Dark/Light Mode**: The site defaults to dark mode and provides a toggle button for users to switch between dark and light themes. Section backgrounds and text colors adapt automatically.
4. **Enhanced Styling**: Navigation, buttons, sections, and featured images use Bootstrap classes for a cohesive and polished appearance.

## Testing
- The site was tested for:
  - **Responsiveness**: Layout adapts to mobile, tablet, and desktop screens.
  - **Accessibility**: Sufficient color contrast and semantic HTML are used. The theme toggle is keyboard accessible.
  - **Dark/Light Mode**: All content remains readable and visually appealing in both modes.

## Custom Styles
- `.section-style` class is used for main content sections to ensure proper background and text color in both themes.
- Additional custom CSS is included for minor layout and color adjustments.

## How to Update Styling
- Use Bootstrap utility classes and components for new sections or features.
- Adjust the `.section-style` class in the `<style>` block of `index.html` for further customization.

---
_Last updated: May 28, 2025_
