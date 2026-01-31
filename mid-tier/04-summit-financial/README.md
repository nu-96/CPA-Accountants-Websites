# Summit Financial Group Template

A professional multi-page website template for established CPA firms with multiple services.

**Tier:** Mid ($1,000-$1,500)  
**Type:** Multi-page with blog

## Pages Included

1. **index.html** - Homepage with hero, services overview, testimonials
2. **services.html** - Detailed services page with categories
3. **about.html** - Company story, values, and team profiles
4. **blog.html** - Blog layout with categories and newsletter signup
5. **contact.html** - Contact form and location information

## Features

- ✅ Multi-page navigation
- ✅ Top bar with contact info and client portal link
- ✅ Sticky navigation
- ✅ Trust indicators section
- ✅ Service cards with hover effects
- ✅ Team member profiles
- ✅ Blog layout with featured post
- ✅ Newsletter subscription form
- ✅ Comprehensive contact form
- ✅ Map placeholder
- ✅ Mobile responsive
- ✅ CSS variables for branding

## Quick Start

1. Edit `css/styles.css` to change brand colors
2. Replace placeholder content across all pages
3. Add team photos and images to `assets` folder
4. Update navigation links if renaming pages
5. Integrate with form handling service
6. Add Google Maps embed

## Customization Guide

### Colors
```css
:root {
    --color-primary: #1a4b8c;   /* Deep blue */
    --color-accent: #f5b041;    /* Gold */
    --color-dark: #1a202c;      /* Navy */
}
```

### Navigation
Update all 5 HTML files when changing navigation links.

### Blog Integration
The blog page is static HTML. For a dynamic blog:
- Integrate with a CMS (WordPress, Contentful, etc.)
- Or manually create individual blog post HTML files

### Forms
Replace form actions with your preferred solution:
- Formspree, Netlify Forms, or custom backend

### Content Checklist
- [ ] Company name and logo
- [ ] Hero text and images
- [ ] Service descriptions
- [ ] Team bios and photos
- [ ] Blog articles
- [ ] Testimonials (with permission)
- [ ] Contact information
- [ ] Google Maps embed

## File Structure

```
04-summit-financial/
├── index.html          # Homepage
├── services.html       # Services page
├── about.html          # About page
├── blog.html           # Blog listing
├── contact.html        # Contact page
├── css/
│   └── styles.css      # Custom styles
├── assets/             # Images folder
└── README.md
```

## License

Template for client website development.
