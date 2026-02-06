# Manila FAME 2026 - Buyer Campaign Landing Page

A visually compelling and user-friendly landing page designed to attract international and local buyers to the Manila FAME trade event. This project showcases modern design principles while reflecting the prestige and cultural richness of Philippine craftsmanship.


## Overview

**Manila FAME** is the Philippines' premier international trade show for home, fashion, and lifestyle products. This landing page serves as a digital campaign to engage potential buyers—wholesalers, retailers, interior designers, architects, and lifestyle-brand sourcing agents.

### Live Demo

Open `index.html` in your browser to view the landing page.

---

## Features

- **Responsive Design** — Optimized for desktop, tablet, and mobile devices
- **Video Hero Section** — Full-width video background with rotating clips showcasing Filipino craftsmanship
- **Animated Typography** — Typed.js integration for dynamic headline effects
- **Interactive Portfolio** — Isotope-powered filterable product categories
- **Testimonials Carousel** — Swiper slider featuring international buyer testimonials
- **Smooth Animations** — AOS (Animate on Scroll) effects throughout the page
- **Lightbox Gallery** — GLightbox for immersive image viewing
- **Live Statistics** — PureCounter animated number counters

---

## Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Bootstrap | 5.3.7 | CSS Framework & Grid System |
| Swiper | Latest | Testimonials Carousel |
| Isotope | Latest | Portfolio Filtering |
| AOS | Latest | Scroll Animations |
| GLightbox | Latest | Image Lightbox |
| Typed.js | Latest | Text Animation |
| PureCounter | Latest | Animated Counters |
| Bootstrap Icons | Latest | Icon Library |

---

## Design Specifications

### Color Palette

The design uses a sophisticated palette blending earthy Filipino tones with vibrant cultural accents:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Warm Off-White | `#faf8f5` | Background |
| Deep Brown | `#2d2926` | Body Text |
| Rich Dark Brown | `#1a1512` | Headings |
| Golden Brown | `#b8860b` | Primary Accent |
| Coral/Terracotta | `#c75b39` | Secondary Accent |
| Deep Forest Green | `#2d5a4a` | Sustainability Accent |
| Warm Beige | `#f5f0e8` | Light Backgrounds |

### Typography

| Font | Type | Usage |
|------|------|-------|
| **Playfair Display** | Serif | Headlines & Titles |
| **Lato** | Sans-serif | Body Text |
| **Montserrat** | Sans-serif | Navigation |

---

## Page Sections

1. **Hero Section** — Video background, animated headline, dual CTAs, event info badges
2. **Why Visit Manila FAME** — Value proposition with statistics and featured image
3. **Benefits Section** — Icon-based highlights (Source Directly, Discover Trends, Sustainable, Exclusive Access)
4. **Partners Section** — Collaboration logos
5. **Featured Exhibitors** — Product showcase grid with exhibitor details
6. **Event Categories** — Filterable portfolio (Furniture & Home, Fashion & Accessories, Gifts & Lifestyle)
7. **Testimonials** — International buyer quotes with carousel
8. **Registration CTA** — Final call-to-action with event countdown
9. **Footer** — Newsletter signup, quick links, event info, contact details, social media

---

## Project Structure

```
LandingPage/
├── index.html              # Main landing page
├── README.md               # Project documentation
├── assets/
│   ├── css/
│   │   └── main.css        # Custom styles & CSS variables
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   ├── img/
│   │   ├── about/          # About section images
│   │   ├── bg/             # Background images
│   │   ├── clients/        # Partner logos
│   │   ├── features/       # Feature images
│   │   ├── person/         # Testimonial photos
│   │   ├── portfolio/      # Product/category images
│   │   ├── services/       # Exhibitor images
│   │   └── video/          # Hero background videos
│   ├── scss/               # SCSS source files
│   └── vendor/             # Third-party libraries
│       ├── aos/
│       ├── bootstrap/
│       ├── bootstrap-icons/
│       ├── glightbox/
│       ├── imagesloaded/
│       ├── isotope-layout/
│       ├── purecounter/
│       ├── swiper/
│       └── typed.js/
└── forms/
    ├── contact.php         # Contact form handler
    └── newsletter.php      # Newsletter subscription handler
```

---

## Getting Started

### Prerequisites

No build tools required. This is a static HTML/CSS/JS project.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/manila-fame-landing-page.git
   ```

2. Open `index.html` in your browser, or serve it using a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000` in your browser.

---

## Customization

### Changing Colors

Edit the CSS variables in `assets/css/main.css`:

```css
:root { 
  --background-color: #faf8f5;
  --default-color: #2d2926;
  --heading-color: #1a1512;
  --accent-color: #b8860b;
  --accent-secondary: #c75b39;
  --accent-tertiary: #2d5a4a;
}
```

### Changing Fonts

Update the Google Fonts import in `index.html` and the font variables in `main.css`:

```css
:root {
  --default-font: "Lato", sans-serif;
  --heading-font: "Playfair Display", serif;
  --nav-font: "Montserrat", sans-serif;
}
```

### Updating Hero Videos

Replace video files in `assets/img/video/` and update the video array in `index.html`:

```javascript
const videos = [
  'assets/img/video/video-2.mp4',
  'assets/img/video/video-1.mp4',
];
```

---

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

---

## Credits

- **Template Base:** [LeadPage by BootstrapMade](https://bootstrapmade.com/leadpage-bootstrap-landing-page-template/)
- **Icons:** [Bootstrap Icons](https://icons.getbootstrap.com/)
- **Fonts:** [Google Fonts](https://fonts.google.com/)

---


