# Construkt Landing Page

A modern, animated landing page for **Construkt** — a premium construction company. Built with semantic HTML, Tailwind CSS (CDN), and GSAP for buttery-smooth animations.

Live Preview: Open `index.html` in any browser.

---

## Features

- **Custom Cursor** — Dot + ring cursor with contextual text on hover
- **Smooth Scrolling** — Lenis-based smooth scroll with parallax effects
- **Hero Animations** — GSAP-powered load animations, word rotation, and scroll parallax
- **Menu Overlay** — Full-screen animated menu with GSAP timelines and X-close button
- **Scroll Reveals** — Staggered fade-in animations on every section
- **Testimonials Marquee** — Dual-row horizontal marquee (desktop) / vertical marquee (mobile)
- **Animated Beam** — Gradient beam animation connecting workflow phases
- **Terminal Component** — macOS-style terminal with sequential line reveal
- **Stats Counter** — Animated number count-up on scroll
- **Highlighter Effect** — Blue highlight bar animation on key text
- **Responsive Design** — Fully responsive across all screen sizes

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 (semantic) |
| Styling | Tailwind CSS v3 (CDN) |
| Animation | GSAP 3 + ScrollTrigger |
| Smooth Scroll | Lenis |
| Fonts | DM Sans (Google Fonts) |
| Images | Unsplash / Picsum (placeholder) |

---

## Project Structure

```
constukt-landingpage/
├── index.html          # Single-file landing page (HTML + CSS + JS)
├── DESIGN.md           # Design system tokens & guidelines
├── .gitignore
└── README.md
```

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Header | Fixed header with logo, nav, and hamburger menu |
| 2 | Hero | Full-screen hero with parallax image and word rotation |
| 3 | About | Company intro with highlighter effect |
| 4 | Services | 4-column service grid with icons |
| 5 | Projects | 2-column project grid with auto-numbered labels |
| 6 | Process | 3-step process with numbered cards |
| 7 | Stats | Animated counters (150+, 200M+, 25+, 98%) |
| 8 | Testimonials | Client reviews in marquee layout |
| 9 | Contact | Form + terminal component |
| 10 | Workflow | Animated beam connecting 5 project phases |
| 11 | Footer | Nav links, brand info, decorative wordmark |

---

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/sufyaan-ahmed/Constukt-landingpage.git
   ```

2. Open `index.html` in your browser — no build step needed.

---

## Customization

All content is placeholder. To customize:

- **Colors** — Edit Tailwind config in `<script>` tag (bone-white, navy-ink, etc.)
- **Fonts** — Change Google Fonts link and CSS variables
- **Images** — Replace Unsplash URLs with your own
- **Text** — Edit directly in the HTML
- **Animations** — Adjust GSAP timelines in the `<script>` section

---

## License

Free to use. Built by [Sufyan Ahmed](https://github.com/sufyaan-ahmed).
