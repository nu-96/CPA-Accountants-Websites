# CPA Website Templates

Professional website templates for accountants and CPA firms. 10 templates across 3 pricing tiers, built with Tailwind CSS for easy customization.

## Template Tiers

### 💼 Budget Tier ($500-$750)
Simple, clean templates perfect for solo practitioners and small firms.

| Template | Description |
|----------|-------------|
| `starter-clean` | Clean single-page, essential sections |
| `modern-minimal` | Minimalist design, bold typography |
| `classic-trust` | Traditional, trust-focused layout |

**Features:**
- Single-page layouts
- Contact form
- Services section
- About section
- Mobile responsive
- Easy color customization

---

### 🏢 Mid Tier ($1,000-$1,500)
Multi-page templates with more features for growing firms.

| Template | Description |
|----------|-------------|
| `professional-multi` | Full multi-page site, dropdown nav |
| `growth-focused` | Lead generation focused, CTAs |
| `industry-expert` | Showcase expertise & testimonials |
| `modern-corporate` | Corporate feel, team pages |

**Features:**
- Multi-page structure (Home, Services, About, Team, Blog, Contact)
- Blog/resources section ready
- Testimonials slider
- Team member pages
- Service detail pages
- Lead capture forms
- Social media integration
- Newsletter signup

---

### 👔 Premium Tier ($2,000-$2,500+)
Full-featured templates for established firms wanting a premium presence.

| Template | Description |
|----------|-------------|
| `executive-suite` | Luxury feel, animations, dark theme |
| `enterprise-pro` | Large firm, multiple offices |
| `wealth-advisor` | High-net-worth client focused |

**Features:**
- All Mid Tier features, plus:
- Scroll animations (AOS library)
- Client portal page ready
- Industry specialization pages
- Case studies section
- Careers page
- Multi-location support
- Video backgrounds
- Advanced contact forms
- Booking/scheduling integration ready
- SEO optimized structure

---

## Quick Start

1. Choose a template from the tier that fits your budget
2. Copy the template folder
3. Open `index.html` and find/replace the placeholders:

```
{{FIRM_NAME}}     → Your firm name
{{PHONE}}         → Phone number
{{EMAIL}}         → Email address
{{ADDRESS}}       → Office address
{{YEARS}}         → Years in business
{{CLIENTS}}       → Number of clients
{{ABOUT_TEXT}}    → About paragraph
{{YEAR}}          → Current year (for copyright)
```

4. Customize colors in the Tailwind config at the top of each HTML file
5. Replace placeholder images with your own
6. Deploy to any static host

---

## Customization Guide

### Colors
Each template uses Tailwind CSS with custom colors defined in the `<script>` tag:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#1e3a5f',    // Main brand color
                secondary: '#2d5a87',  // Secondary/hover
                accent: '#4a90a4',     // Accent/highlights
            }
        }
    }
}
```

### Fonts
Premium templates include Google Fonts. Change the font family in the `<link>` and CSS.

### Images
All templates use Unsplash placeholder images. Replace with your own:
- Hero images: 1920x1080 recommended
- Team photos: 400x500 recommended
- About images: 600x400 recommended

---

## Deployment Options

These are static HTML templates. Deploy to:
- **Netlify** (free tier available)
- **Vercel** (free tier available)
- **GitHub Pages** (free)
- **AWS S3 + CloudFront**
- Any web hosting provider

---

## File Structure

```
cpa-templates/
├── README.md
├── budget-tier/
│   ├── starter-clean/
│   │   ├── index.html
│   │   └── README.md
│   ├── modern-minimal/
│   │   └── index.html
│   └── classic-trust/
│       └── index.html
├── mid-tier/
│   ├── professional-multi/
│   │   ├── index.html
│   │   ├── services.html
│   │   ├── about.html
│   │   ├── team.html
│   │   ├── blog.html
│   │   └── contact.html
│   ├── growth-focused/
│   ├── industry-expert/
│   └── modern-corporate/
└── premium-tier/
    ├── executive-suite/
    │   ├── index.html
    │   ├── services.html
    │   ├── industries.html
    │   ├── team.html
    │   ├── insights.html
    │   ├── contact.html
    │   └── portal.html
    ├── enterprise-pro/
    └── wealth-advisor/
```

---

## Support

These templates are designed to be customized for your clients. Each client deployment should be treated as a unique project with:
- Custom colors matching their brand
- Their own copy and images
- Appropriate contact forms connected to their email
- Any additional pages they need

---

## License

These templates are proprietary to Luniero. Use for client projects only.
