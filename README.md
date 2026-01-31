# CPA & Accountant Website Templates

Professional, modern website templates designed specifically for CPA firms, accountants, and financial advisory practices.

## 📁 Template Overview

### Budget Tier ($500-$750)
Simple, clean single-page or minimal multi-page designs perfect for solo practitioners and small firms.

| Template | Description | Key Features |
|----------|-------------|--------------|
| **01-essential-cpa** | Classic professional single-page | Hero, services, testimonials, contact form |
| **02-clarity-accounting** | Modern minimalist design | Stats bar, emoji icons, transparent pricing feel |
| **03-trustpoint-cpa** | Trust-focused with personal branding | CPA bio section, trust badges, 6 services |

### Mid Tier ($1,000-$1,500)
Multi-page websites with blog capabilities, more sophisticated layouts, and additional features.

| Template | Description | Pages | Key Features |
|----------|-------------|-------|--------------|
| **04-summit-financial** | Professional multi-page | 5 pages | Blog, team profiles, comprehensive contact |
| **05-precision-tax** | Strategy-focused | 5 pages | Industry expertise, resources section, newsletter |
| **06-heritage-advisors** | Elegant family wealth | 5 pages | Serif typography, generational messaging, warm palette |
| **07-smallbiz-cpa** | Small business focused | 5 pages | Pricing table, transaction-based tiers, free resources |

### Premium Tier ($2,000-$2,500+)
Full-featured templates with animations, modern effects, and enterprise-grade design.

| Template | Description | Key Features |
|----------|-------------|--------------|
| **08-apex-advisory** | Enterprise-grade | AOS animations, dropdown nav, video placeholder, gradient hero |
| **09-nexus-partners** | Startup/tech-focused | Dark theme, glassmorphism, scroll-responsive nav |
| **10-meridian-wealth** | Ultra-luxury private client | Serif typography, asymmetric layout, editorial design |

## 🛠 Technology Stack

All templates use:
- **Tailwind CSS** (via CDN for easy customization)
- **CSS Custom Properties** for brand colors and fonts
- **Responsive Design** (mobile-first)
- **Semantic HTML5**

Premium templates additionally include:
- **AOS (Animate on Scroll)** library
- **Google Fonts** integration
- **Modern CSS** (backdrop-filter, gradients, animations)

## 🎨 Customization

### Quick Color Change

Each template uses CSS variables in the `css/styles.css` file:

```css
:root {
    --color-primary: #1e3a5f;    /* Main brand color */
    --color-secondary: #4a6fa5;  /* Secondary color */
    --color-accent: #d4a84b;     /* Accent/highlight color */
}
```

Simply update these values to match your client's brand.

### Typography

Most templates use system fonts by default. Premium templates include Google Fonts. To change fonts:

1. Update the `<link>` tag in the HTML head
2. Modify the `--font-heading` and `--font-body` CSS variables

### Content Replacement Checklist

For each template, replace:
- [ ] Company name and logo
- [ ] Hero headline and description
- [ ] Service descriptions
- [ ] Team bios and photos
- [ ] Testimonials (with permission)
- [ ] Contact information
- [ ] Footer details

## 📱 Responsive Breakpoints

All templates are responsive with breakpoints at:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 📂 File Structure

Each template follows this structure:

```
template-name/
├── index.html          # Main page
├── services.html       # (Multi-page only)
├── about.html          # (Multi-page only)
├── contact.html        # (Multi-page only)
├── css/
│   └── styles.css      # Custom styles & variables
├── js/                 # (Premium only)
├── assets/             # Images, fonts, etc.
└── README.md           # Template-specific docs
```

## 🚀 Getting Started

1. Choose a template based on budget and needs
2. Copy the template folder to your project
3. Open `css/styles.css` and update brand colors
4. Replace placeholder content in HTML files
5. Add images to the `assets` folder
6. Test on multiple devices
7. Deploy!

## 🔌 Integration Notes

### Forms
Replace form `action` attributes with your preferred backend:
- [Formspree](https://formspree.io)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- Custom backend API

### Analytics
Add tracking before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
```

### Production Optimization
For production deployment:
1. Minify CSS and JS
2. Optimize images (WebP format recommended)
3. Consider self-hosting Tailwind CSS (built version)
4. Enable GZIP compression
5. Add appropriate meta tags for SEO

## 📄 License

These templates are provided for client website development.

## 🤝 Support

For customization assistance or questions, contact the development team.

---

*Created for CPA and accounting professionals who want professional, modern websites without the enterprise price tag.*
