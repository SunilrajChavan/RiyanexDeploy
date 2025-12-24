# Riyanex Static Website

This is a static HTML version of the Riyanex website, matching the design and functionality of the React application.

## Features

- **Responsive Design**: Fully responsive on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Smooth anchor navigation between sections
- **Modern Styling**: Gradient text, glass-morphism effects, and smooth transitions
- **Contact Form**: Functional form with client-side validation and submission handling
- **Icon Support**: Uses Font Awesome icons (CDN)
- **Accessibility**: Semantic HTML with proper form labels and ARIA attributes

## File Structure

```
StaticPage/
├── index.html          # Main HTML file with all content
├── css/
│   ├── variables.css   # CSS custom properties and theme variables
│   └── styles.css      # All styling rules
└── images/
    └── logo.png        # Riyanex logo
```

## Sections

1. **Navigation Bar** - Sticky navigation with smooth scrolling links
2. **Hero Section** - Main call-to-action with headline and CTAs
3. **Services** - 6 service cards showcasing company expertise
4. **About** - Company info with values/core pillars
5. **Mission** - Company mission statement
6. **Contact** - Contact form and company contact information

## Usage

Simply open `index.html` in a web browser. The website is completely self-contained with no build process required.

### Local Testing

For best results with local testing:
```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server
```

Then visit `http://localhost:8000`

## Customization

All colors and styles can be modified in `css/variables.css` and `css/styles.css`. The design uses CSS custom properties (CSS variables) for easy theming.

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers
