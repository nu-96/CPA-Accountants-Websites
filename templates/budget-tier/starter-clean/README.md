# Starter Clean Template
**Price Tier:** Budget ($500-$750)

## Overview
A clean, single-page website template perfect for small CPA firms and individual accountants. Professional appearance with essential sections only.

## Features
- Single-page layout with smooth scrolling
- Hero section with call-to-action
- Services showcase (3 services)
- About section with image
- Contact form
- Trust badges
- Mobile responsive

## Customization Guide

### Colors
Edit the Tailwind config in `<script>` tag:
```javascript
colors: {
    primary: '#1e3a5f',    // Main brand color (navy)
    secondary: '#2d5a87',  // Hover states
    accent: '#4a90a4',     // Highlights
    light: '#f8fafc'       // Background
}
```

### Placeholders to Replace
- `{{FIRM_NAME}}` - Your firm name
- `{{YEARS}}` - Years in business
- `{{CLIENTS}}` - Number of clients served
- `{{ABOUT_TEXT}}` - About paragraph
- `{{ADDRESS}}` - Office address
- `{{PHONE}}` - Phone number
- `{{EMAIL}}` - Email address
- `{{YEAR}}` - Current year

### Images
Replace the Unsplash placeholder with your own:
- About section image: 600x400px recommended

## File Structure
```
starter-clean/
├── index.html
└── README.md
```

## Deployment
This template is static HTML with Tailwind via CDN. Deploy to any static host:
- Netlify
- Vercel
- GitHub Pages
- Any web server
