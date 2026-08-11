# Appliance Rescue Pro

A responsive, premium single-page website for **Appliance Rescue Pro**, a 24/7 domestic appliance repair service in London NW4.

## Overview

This project is a standalone HTML landing page designed to promote appliance repair services and generate customer enquiries/calls.

### Business details

- **Business:** Appliance Rescue Pro
- **Service area:** London NW4
- **Availability:** 24/7 emergency appliance repair
- **Technician:** Mehdi
- **Phone:** 07599 929733
- **Services:** Washing machine, fridge, freezer, and dishwasher repairs

## Features

- Responsive mobile-first layout
- Sticky, translucent navigation header
- Premium light visual theme
- Amber accent colour palette
- Accessible focus states
- Reduced-motion support
- Smooth scrolling
- Responsive typography using CSS `clamp()`
- Reusable button and layout styles
- Google Fonts integration:
  - Outfit
  - Inter
  - EB Garamond
- SEO-friendly page title and meta description
- Service-focused calls to action

## Project Structure

```text
.
└── index.html    # Complete website, including HTML, CSS, and JavaScript
```

## Getting Started

No build tools or dependencies are required.

### Option 1 — Open directly

Open `index.html` in a modern web browser.

### Option 2 — Run a local server

From the project directory:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts

The site does not require React, Node.js, npm, or a frontend build system.

## Customisation

Most of the visual design tokens are defined in the `:root` section of `index.html`, including:

- Colours
- Typography
- Container widths
- Border radii
- Shadows
- Animation easing

For example:

```css
:root {
  --bg: #FBFAF6;
  --text: #1A1A1A;
  --accent: #B45309;
  --container: 1280px;
}
```

Update these variables to quickly adjust the site's overall visual style.

## Fonts

The page currently loads fonts from Google Fonts. An internet connection is therefore recommended for the intended typography.

If self-hosting is required, download the selected fonts and update the font-face declarations accordingly.

## SEO

The page includes:

- A descriptive `<title>`
- A meta description
- Responsive viewport configuration
- Semantic HTML structure

Current page title:

> Appliance Rescue Pro | 24/7 Appliance Repair Service in London NW4

Current description:

> Fast, reliable washing machine, fridge, freezer, and dishwasher repairs in London NW4. 24/7 emergency service by expert technician Mehdi. Call 07599 929733.

## Deployment

Because this is a static HTML website, it can be deployed to most static hosting providers or traditional web hosting.

Typical deployment steps:

1. Upload `index.html` to the website's public/root directory.
2. Ensure the file is served as the site's homepage.
3. Confirm all phone/contact links work.
4. Test the layout on mobile, tablet, and desktop.
5. Verify fonts and any external assets load correctly.

## Browser Support

The page is intended for current versions of:

- Chrome
- Edge
- Firefox
- Safari
- Mobile Safari
- Chrome for Android

## Accessibility

The stylesheet includes:

- Visible keyboard focus indicators
- Reduced-motion support via `prefers-reduced-motion`
- Responsive text sizing
- Semantic heading and section structure

When making further changes, preserve sufficient colour contrast and keyboard accessibility.

## Notes

This README documents the supplied `index.html` as a self-contained static website. Any additional assets, backend functionality, booking systems, analytics, or form-processing services should be documented here if they are added later.

## License

No license was specified in the supplied project. Add an appropriate license here if this project will be distributed or reused.
