# Squeaky Kleen Landing Page

A modern, responsive, and accessible landing page for Squeaky Kleen, a professional cleaning service in Nigeria. This project is built with HTML, Tailwind CSS, and vanilla JavaScript, and is ready for deployment on any static hosting platform (Vercel, Netlify, GitHub Pages, etc.).

## Features
- Responsive design for desktop and mobile
- Sticky navigation with smooth scroll and mobile menu
- Rotating hero image (configurable interval)
- Services, testimonials (with Swiper slider), FAQ, and gallery sections
- Accessible forms with validation and spam protection
- NDPA-compliant privacy policy modal
- SEO meta tags and structured data (JSON-LD)
- Social media and WhatsApp integration
- Newsletter signup (Formcarry-ready)

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (optional, for Tailwind production build)

### Folder Structure
```
index.html
main.css
main.js
img/
  favicon.jpg
  Squeaky Logomark_vector.svg
  qrcode.png
  hero-cleaning.jpg
  stock/
    ... (gallery/hero images)
```

### Running Locally
1. Clone the repo:
   ```
   git clone https://github.com/yourusername/squeaky-kleen.git
   cd squeaky-kleen
   ```
2. Open `index.html` in your browser.

### Tailwind Production Build (Optional)
1. Install dependencies:
   ```
   npm install
   ```
2. Build CSS:
   ```
   npm run build:css
   ```
3. Deploy the contents to your static host.

## Deployment
- Deploy to [Vercel](https://vercel.com/), [Netlify](https://netlify.com/), or [GitHub Pages](https://pages.github.com/).
- No backend required for basic operation.

## Forms
- Contact and newsletter forms are ready for [Formcarry](https://formcarry.com/) or similar services. Replace the `action` attribute with your endpoint.

## Customization
- Update images in the `img/` and `img/stock/` folders.
- Edit hero image rotation interval in `main.js` (`TIMER_HOURS`).
- Add or update FAQ, gallery, and testimonials in `index.html`.
- Update social media links in the footer.

## Accessibility & Compliance
- Keyboard navigation and focus management
- Color contrast and ARIA labels
- NDPA-compliant privacy policy

## License
MIT

## Authors

- [Warren] (https://github.com/Olabomi) — Lead Developer

## Contributors

Thanks to everyone who contributed!

---

**Squeaky Kleen** — Professional Cleaning Services in Nigeria
