# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all devices
- Modern and clean UI with smooth animations
- Interactive navigation with smooth scrolling
- Skills showcase with hover effects
- Contact form with validation
- Mobile-friendly navigation menu
- Dynamic copyright year
- Scroll animations for better user experience

## Structure

- `index.html` - Main HTML file containing the website structure
- `styles.css` - CSS styles for layout and design
- `script.js` - JavaScript for interactivity and animations

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content in `index.html` to match your information
4. Modify styles in `styles.css` to match your preferences
5. Update the contact form handling in `script.js` if needed

## Customization

### Adding Projects
To add projects to the portfolio:
1. Find the `projects-grid` div in `index.html`
2. Add project cards following this structure:
```html
<div class="project-card">
    <img src="project-image.jpg" alt="Project Name">
    <h3>Project Name</h3>
    <p>Project description</p>
    <div class="project-links">
        <a href="#" class="btn">View Project</a>
        <a href="#" class="btn">Source Code</a>
    </div>
</div>
```

### Changing Colors
The main colors can be modified in `styles.css`:
- Primary color: `#0984e3`
- Gradient colors: `#6c5ce7` and `#a8e6cf`
- Text color: `#2d3436`

## Browser Support

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 