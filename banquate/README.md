# Bou Thakurani Banquet - Premium Luxury Event Management Website Frontend

A modern, luxurious, premium-quality, fully responsive static HTML5 website frontend built for Bou Thakurani Banquet in Madhyamgram, Kolkata.

Designed for direct static hosting (Hostinger, cPanel, Apache, GoDaddy, GitHub Pages, Netlify, etc.) without any command line build steps, compilation, database, or backend setup.

---

## Folder Structure

```text
banquet-website/
│
├── index.html           # Landing page (with Swiper slider, welcome, categories, video tour, reviews)
├── about.html           # Heritage, milestones, team profiles, and FAQs
├── services.html        # Detailed event hostings grid, Cost Estimator, and Custom Menu Builder
├── gallery.html         # Media gallery with custom filters and GLightbox
├── contact.html         # Google map integration, contact cards, and validation contact form
│
├── assets/
│   ├── css/
│   │   ├── style.css       # Core layout structure, premium typography, colors, animations
│   │   └── responsive.css  # Extracted CSS media queries for full mobile/tablet responsiveness
│   │
│   ├── js/
│   │   ├── script.js       # Core javascript: sticky navbar, custom cursor, Swiper/AOS setup, form validation
│   │   └── jquery.min.js   # Local minified jQuery library
│   │
│   ├── images/
│   │   ├── hero/           # Carousel banners
│   │   ├── gallery/        # Lightbox showcase photos
│   │   ├── services/       # Event service cards
│   │   ├── about/          # Welcome images, leadership profiles, reviewer avatars
│   │   ├── logo.png        # Brand logo
│   │   └── icons/          # Specialty indicators
│   │
│   └── fonts/              # Custom fonts folder
│
├── favicon.ico          # Web page icon
│
└── README.md            # Setup and deployment instructions (this file)
```

---

## Libraries & CDNs Integrated

* **Bootstrap 5.3.3** (CSS & JS bundle via CDN) - Responsive grid, utility layout, modals, and dropdowns.
* **jQuery 3.7.1** (Local) - Minified jQuery library.
* **Bootstrap Icons 1.11.3** (via CDN) - Scalable theme icons.
* **Swiper.js 11** (via CDN) - Premium fade hero slider and touch-enabled testimonial slider.
* **GLightbox 3.3.0** (via CDN) - Elegant lightbox popups for high-res images and virtual video tours.
* **AOS (Animate On Scroll) 2.3.1** (via CDN) - Smooth fade and zoom transitions triggered by page scroll.

---

## How to Run Locally

### Option A: Open Directly
Simply double-click `index.html` in any web browser.

### Option B: Local Web Server
Run a simple local web server in the directory.
* **Using Python:**
  ```bash
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000` in your browser.
* **Using Node:**
  ```bash
  npx http-server
  ```
  Then visit `http://localhost:8080` in your browser.

---

## How to Deploy to Production (Hostinger / cPanel / GitHub Pages)

### Hostinger / cPanel / Netlify / Vercel
1. Compress the entire contents of the root folder (containing the HTML files and the `assets/` folder) into a single ZIP file.
2. Log in to your Hostinger hPanel or cPanel File Manager.
3. Navigate to the `public_html` directory.
4. Upload the ZIP file.
5. Extract the ZIP file directly inside `public_html`.
6. Ensure that the HTML files (`index.html`, `about.html`, etc.) are in the root of the hosting directory.

### GitHub Pages
1. Push this folder structure to a public GitHub repository.
2. Go to repository Settings > Pages.
3. Select the branch (e.g. `main`) and root folder `/` (root), then click Save.

---

## Key Interactive Features Implemented

1. **Elegant Sticky Navbar** with dynamic background blur (glassmorphism) and active navigation highlights.
2. **Immersive Ken Burns fade slider** in Hero section.
3. **Dynamic Budget Estimator & Event Cost Calculator** on services page with instant receipt preview.
4. **Custom Food Menu Builder** with clipboard copy and booking modal attachment capabilities.
5. **Seamless contact form validations** compiling user responses directly to WhatsApp API messages.
6. **Cinematic video tour** opening in lightboxes without page reloads.
7. **Smooth custom gold cursor follower** for premium aesthetic desktop navigation (disabled on touch).
