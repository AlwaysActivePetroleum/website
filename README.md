# Always Active Petroleum Website

A professional and stylish website for Always Active Petroleum, showcasing their premium tanker truck fleet and transportation services.

## Features

- **Professional Design**: Modern, clean layout with gradient themes
- **Responsive Layout**: Fully responsive on desktop, tablet, and mobile devices
- **Mixed Gallery Layouts**: 
  - Full-width hero showcase
  - Side-by-side comparisons
  - Masonry gallery with varying image sizes
  - Large featured images
- **Smooth Animations**: Hover effects, scroll animations, and smooth transitions
- **Interactive Elements**: Navigation, contact form, image zoom effects
- **Accessibility**: Semantic HTML, proper image alt tags, ARIA labels

## Sections

1. **Navigation Bar**: Sticky header with smooth scrolling links
2. **Hero Section**: Eye-catching introduction with CTA button
3. **Fleet Overview**: Mixed layout showcasing all 4 tanker trucks
4. **Services**: Grid of service offerings
5. **Gallery**: Masonry layout with professional imagery
6. **Contact**: Contact information and inquiry form
7. **Footer**: Company info and social links

## Image Setup

Place your 4 truck images in the `/images` folder:

```
images/
├── truck-1.jpg   (Fleet lineup - full width hero)
├── truck-2.jpg   (Blue tanker - side view)
├── truck-3.jpg   (Blue tanker - front view)
└── truck-4.jpg   (White tanker - featured)
```

## Files Structure

```
website/
├── index.html          (Main HTML file)
├── css/
│   └── style.css       (All styling)
├── js/
│   └── script.js       (Interactive features)
├── images/             (Truck photos - add your images here)
└── README.md           (This file)
```

## Customization

### Colors
Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #0066cc;
    --secondary-color: #004c99;
    --accent-color: #ff6b35;
}
```

### Contact Information
Update contact details in the `index.html` contact section:
- Phone number
- Email address
- Physical address

### Gallery Layouts
The gallery uses CSS Grid with various sizing options:
- `.large-horizontal`: 2 columns wide
- `.medium`: Standard square
- `.large-vertical`: 2x2 grid space

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Image lazy loading for faster page loads
- Optimized CSS and JavaScript
- Smooth animations using CSS transforms
- Responsive images for different screen sizes

## License

© 2026 Always Active Petroleum. All rights reserved.