# Essential CPA Template

A clean, professional single-page website template for CPA firms and accounting practices.

**Tier:** Budget ($500-$750)  
**Type:** Single-page landing page

## Features

- ✅ Responsive design (mobile-first)
- ✅ Clean, professional aesthetic
- ✅ Hero section with dual CTAs
- ✅ Services section with icons
- ✅ About section with credentials
- ✅ Client testimonials
- ✅ Contact form
- ✅ Trust badges (CPA, AICPA, experience stats)
- ✅ Tailwind CSS for easy customization
- ✅ CSS variables for branding

## Quick Start

1. Open `css/styles.css`
2. Edit the CSS variables to match your brand:
   ```css
   :root {
       --color-primary: #1e3a5f;    /* Your main color */
       --color-accent: #d4a84b;     /* Your accent color */
       --font-heading: 'Georgia';   /* Your heading font */
   }
   ```
3. Replace placeholder content in `index.html`
4. Add your logo and team photos to the `assets` folder

## Customization Guide

### Colors
Edit the `:root` variables in `css/styles.css`:
- `--color-primary`: Main brand color (nav, buttons, headings)
- `--color-secondary`: Secondary color for lighter elements
- `--color-accent`: Highlight color (stars, checkmarks, accents)

### Fonts
1. Add your fonts via Google Fonts or self-host
2. Update `--font-heading` and `--font-body` variables

### Content to Replace
- [ ] Company name and logo
- [ ] Hero headline and description
- [ ] Service descriptions
- [ ] About section text and credentials
- [ ] Team photo
- [ ] Testimonials (use real client reviews)
- [ ] Contact information
- [ ] Footer links

### Images
Place your images in the `assets` folder:
- `logo.png` - Your company logo
- `team.jpg` - Team or office photo
- `favicon.ico` - Browser tab icon

## File Structure

```
01-essential-cpa/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Custom styles & CSS variables
├── assets/             # Images and media
│   └── (add your images here)
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/) (via CDN)

## License

This template is provided for client website development.
