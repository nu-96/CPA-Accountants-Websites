# Apex Advisory Group - Premium Template

An ultra-premium, enterprise-grade template for elite CPA and advisory firms.

**Tier:** Premium ($2,000-$2,500+)  
**Type:** Full-featured with animations

## Pages Included

Create additional pages following the same structure:
- **index.html** - Feature-rich homepage with animations
- services.html, industries.html, team.html, insights.html, contact.html

## Premium Features

- ✅ AOS (Animate on Scroll) library integration
- ✅ Scroll-responsive navigation
- ✅ Glassmorphism design elements
- ✅ Gradient backgrounds and text
- ✅ Video placeholder with play button
- ✅ Client logo carousel ready
- ✅ Mega menu dropdown navigation
- ✅ Stats dashboard
- ✅ Animated shapes/blobs
- ✅ Modern card hover effects
- ✅ Integration-ready (forms, analytics)

## Technologies

- Tailwind CSS
- AOS (Animate on Scroll)
- Google Fonts (Inter)
- CSS custom properties
- Modern CSS (backdrop-filter, gradients)

## Customization

### Colors
```css
:root {
    --color-primary: #0d47a1;   /* Deep blue */
    --color-accent: #ffc107;    /* Gold */
    --color-dark: #0a1628;      /* Navy */
}
```

### Animations
AOS is initialized with:
```javascript
AOS.init({
    duration: 800,
    once: true,
    offset: 100
});
```

Modify timing in the script tag at the bottom of index.html.

### Adding Pages

Copy the nav, footer, and structure from index.html. Key sections to include:
- Top bar
- Navigation with dropdown
- Page header
- Content sections
- CTA section
- Footer

## Integration Ready

### Form Handling
Replace form action with your backend:
- Formspree
- Netlify Forms
- HubSpot
- Custom API

### Analytics
Add tracking codes before `</head>`:
- Google Analytics
- Google Tag Manager
- Facebook Pixel

### CRM Integration
The contact form is structured for easy CRM integration with:
- HubSpot
- Salesforce
- Pipedrive

## File Structure

```
08-apex-advisory/
├── index.html          # Full homepage
├── css/
│   └── styles.css      # Premium styles
├── js/                  # For custom scripts
├── assets/             # Images, videos
└── README.md
```

## Browser Support

- Chrome, Firefox, Safari, Edge (latest)
- IE11 not supported (uses modern CSS features)

## Performance Notes

- Lazy load images for production
- Consider self-hosting AOS for better performance
- Optimize images before deployment
