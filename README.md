# Al-Khubaib Real Estate — Website

A responsive, single-page website for **Al-Khubaib Real Estate Marketing & Builders (Pvt) Ltd.**, a SECP-registered real estate and construction company based in Rawalpindi, Pakistan.



## Overview

This is a modern, mobile-first real estate website built as a single self-contained HTML file. It showcases the company's housing society project (Margalla Gardens), property listings, construction process, and provides direct contact options via WhatsApp — all without requiring a backend server.

---

## Features

- **Responsive design** — works smoothly on both mobile and desktop
- **Animated hero section** with a rotating image slideshow
- **Sticky navigation** with a mobile hamburger menu
- **Live property search** — filters listings instantly as you type
- **Property listing cards** with WhatsApp inquiry links pre-filled per plot
- **Contact form** that sends messages directly via WhatsApp (no backend needed)
- **FAQ accordion** section using native HTML (no extra JavaScript)
- **Scrolling announcement ticker** for offers and highlights
- **SEO-friendly** — includes meta description and Open Graph tags
- **Accessible** — all images include descriptive alt text

---

## Tech Stack

- **HTML5**
- **CSS3** (custom properties, Flexbox, Grid, responsive media queries)
- **Vanilla JavaScript** (no frameworks or build tools required)
- **Google Fonts** (Poppins)

No npm, no build step, no dependencies — just open the HTML file in a browser.

---

## File Structure

```
client_1/
├── homepage.html     # Main website file (self-contained)
└── README.md         # This file
```

All images are embedded directly in the HTML file as base64 data, so the site works as a single file with no external image assets to manage.

---

## Running Locally

Simply open `homepage.html` in any modern web browser. No server or installation required.

---

## Deployment

This site is ready to be deployed to any static hosting provider, such as:

- Vercel
- Netlify
- GitHub Pages

Once deployed, update the contact details, WhatsApp number, and property listings as needed directly in the HTML file.

---

## Known Limitations

- This is a **static site** — it does not include a backend, database, or admin panel. Property listings are currently hardcoded in the HTML.
- The search bar filters only the properties currently listed on the page.
- For a content management system (so the client can add/edit listings without a developer), a backend (e.g. a small CMS or database-driven admin panel) would need to be added separately.

---

## Contact

**Al-Khubaib Real Estate Marketing & Builders (Pvt) Ltd.**
Faisal Colony, Near Attock Petrol Pump, Airport Link Road, Rawalpindi
📞 0301-5013090
SECP Registered — CUIN 0153338
