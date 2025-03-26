# Fort Worth Zendo Website

A simple, responsive single-page website for the Fort Worth Zendo.

## Features

- Clean, minimalist design with dark muted colors
- Responsive layout that works on all devices
- Smooth scrolling navigation
- Three main sections: Home, When & Where, and Contact
- Mobile-friendly design

## Customization

### Colors
The website uses a dark, muted color scheme defined in `styles.css`. You can modify the colors by changing the CSS variables in the `:root` selector:

```css
:root {
    --color-bg: #1a1a1a;        /* Background color */
    --color-text: #e0e0e0;      /* Main text color */
    --color-accent: #8b7355;    /* Accent color for headings */
    --color-secondary: #2d2d2d; /* Secondary background color */
    --color-muted: #666666;     /* Muted text color */
}
```

### Content
To update the content, edit the `index.html` file. The main sections are:
- Home section: Update the introduction text
- When & Where section: Add your schedule and location details
- Contact section: Update the contact information

### Adding a Map
To add a map to the When & Where section:
1. Replace the `map-placeholder` div with your preferred map embed code (Google Maps, Mapbox, etc.)
2. Adjust the `map-container` height in `styles.css` if needed

## Development

The website is built with:
- HTML5
- CSS3 (with CSS variables for easy customization)
- Vanilla JavaScript (for smooth scrolling and navbar effects)

No build process is required - simply serve these files from any web server.

## Deployment

You can deploy this website to any static hosting service such as:
- GitHub Pages
- Netlify
- Vercel
- Any traditional web hosting

## License

This project is open source and available under the MIT License. 