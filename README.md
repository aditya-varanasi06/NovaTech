# NovaTech — Responsive Website

A clean, modern, mobile-friendly landing page built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies — just fast, responsive web design.

---

## Features

- **Sticky Header** with logo and navigation links
- **Hamburger Menu** for mobile navigation (toggle on small screens)
- **Hero Section** with headline, subtext, CTA button, and image
- **Features Section** with a 3-column card grid
- **Testimonials Section** with a client quote
- **Pricing Section** with three pricing tier cards (Starter, Professional, Enterprise)
- **Contact Section** with name, email, and message fields
- **Scroll Animations** — elements fade in as they enter the viewport via `IntersectionObserver`
- **Responsive Layout** — adapts to all screen sizes using CSS media queries

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Grid, Flexbox, Media Queries) |
| Scripting | Vanilla JavaScript |
| Font | Google Fonts — Poppins |
| Images | Picsum Photos (placeholder) |

---

## Project Structure

```
project/
└── index.html      # Single-file application (HTML + CSS + JS)
```

---

## Getting Started

No build tools or dependencies required.

1. **Clone or download** the project
2. Open `index.html` in any modern browser

```bash
# Optional: serve locally with Python
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

---

## Responsive Breakpoints

| Breakpoint | Behaviour |
|---|---|
| `> 768px` | Full desktop layout — horizontal nav, 3-column grids, side-by-side hero |
| `≤ 768px` | Mobile layout — hamburger menu, stacked single-column grid, centered hero |

---

## Sections Overview

| Section | ID | Description |
|---|---|---|
| Header | — | Sticky nav with logo and links |
| Hero | — | Headline, description, CTA, and image |
| Features | `#features` | Three feature highlight cards |
| Testimonials | — | Client quote block |
| Pricing | `#pricing` | Three pricing tier cards |
| Contact | `#contact` | Simple inquiry form |
| Footer | — | Copyright notice |

---

## Customization

All colors are managed via CSS custom properties in `:root`:

```css
:root {
  --bg: #0f172a;           /* Page background */
  --card: #020617;         /* Card / header background */
  --primary: #38bdf8;      /* Accent color */
  --primary-dark: #0ea5e9; /* Hover accent color */
  --text: #f1f5f9;         /* Primary text */
  --muted: #cbd5f5;        /* Secondary / muted text */
}
```

Swap these values to instantly retheme the entire site.

---

## License

© 2026 NovaTech. All rights reserved.
