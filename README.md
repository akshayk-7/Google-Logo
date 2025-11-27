# Google Logo - CSS Art Project

A creative CSS-based recreation of the Google "G" logo using pure HTML and CSS.

## Project Overview

This project demonstrates the power of CSS for creating complex shapes and designs. The Google "G" logo is created using:
- A circular border with rounded corners
- CSS pseudo-elements (`::before` and `::after`) for the opening and horizontal bar
- Multi-color gradient effect using RGB color values

## Features

- **Pure CSS Design**: No images or SVG files - entirely built with HTML and CSS
- **Responsive Layout**: Centered on the page with flexbox
- **Multicolor Logo**: Features the iconic Google colors:
  - Red: `rgb(240, 12, 12)`
  - Blue: `rgb(20, 129, 188)`
  - Green: `rgb(39, 234, 52)`
  - Yellow: `rgb(238, 189, 11)`

## File Structure

```
Google/
├── index.html    - HTML structure with the logo div
└── style.css     - CSS styling and animations
```

## HTML Structure

The HTML is minimal and clean:
- A single `<div>` element serves as the canvas for the CSS design
- Meta tags for UTF-8 encoding and viewport configuration
- External stylesheet reference

## CSS Techniques Used

### Main Logo Container
```css
div {
  width: 200px;
  height: 200px;
  border: 25px solid;
  border-radius: 50%;
  position: relative;
  box-sizing: border-box;
  background: white;
  border-color: rgb(240, 12, 12) rgb(20, 129, 188) rgb(39, 234, 52) rgb(238, 189, 11);
}
```

### Opening on the Right (Pseudo-element `::before`)
Creates the gap that transforms the circle into a "G" shape by using a white background positioned absolutely.

### Horizontal Bar (Pseudo-element `::after`)
Adds the characteristic horizontal bar at the bottom right of the logo with a skewed transform for visual interest.

## How to Use

1. Open `index.html` in any modern web browser
2. The Google "G" logo will be displayed in the center of the page
3. The design is responsive and will maintain its aspect ratio

## Browser Support

Works on all modern browsers that support:
- CSS Flexbox
- CSS Pseudo-elements
- CSS Border styling with multiple colors
- CSS Transform properties

## Learning Resources

This project demonstrates:
- CSS positioning (absolute, relative)
- CSS pseudo-elements for creating additional elements without HTML
- CSS border manipulation
- CSS transforms (skew)
- CSS flexbox for centering
- Box model and `box-sizing`

## Future Enhancements

- Add animations and transitions
- Create variations with different hover effects
- Build a complete Google logo with multiple letters
- Add interactive elements

## Author

Created as a CSS art and design exploration project.

---

**Note**: This is a fan-made CSS recreation of the Google logo for educational purposes.
