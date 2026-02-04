# Cursor Landing Page Clone

A static clone of the [Cursor](https://cursor.com) marketing landing page, built with HTML and CSS. The page mirrors the structure, layout, and visual style of the official Cursor homepage.

---

## What's Included

This project recreates the following sections from the Cursor landing page:

| Section                 | Description                                                                                                                                                    |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Header / Navigation** | Sticky nav with Cursor logo, links (Features, Enterprise, Pricing, Resources), and Sign in / Download buttons.                                                 |
| **Hero**                | Main headline ("Built to make you extraordinarily productive…"), primary CTA (Download for Windows), and hero IDE screenshot.                                  |
| **Logo Garden**         | "Trusted every day by millions of professional developers" with partner logos (Stripe, OpenAI, Linear, Datadog, NVIDIA, Figma, Ramp, Adobe).                   |
| **Features**            | Three feature blocks: Agent, Magically accurate autocomplete (Tab), and Cursor's ecosystem, each with image and "Learn more" link.                             |
| **Testimonials**        | "The new way to build software" heading with a grid of 6 testimonial cards (Diana Hu, shadcn, Andrej Karpathy, Patrick Collison, ThePrimeagen, Greg Brockman). |
| **Use Cases**           | "Stay on the frontier" with three cards: Access the best models, Codebase understanding, and Develop enduring software.                                        |
| **Changelog**           | Changelog section with four version/date entries and a "See what's new" link.                                                                                  |
| **About**               | "Cursor is an applied team…" copy, "Join us →" CTA, and team photo.                                                                                            |
| **CTA**                 | Full-width "Try Cursor now." block with download button.                                                                                                       |
| **Footer**              | Five columns (Product, Resources, Company, Legal, Connect) and credits (© 2026 Cursor, SOC 2 Certified).                                                       |

---

## Design Tokens

### Fonts

- **Primary font:** [Carrois Gothic](https://fonts.google.com/specimen/Carrois+Gothic) (Google Fonts), used for all body and heading text.

### Colors

Defined in `style.css` via CSS custom properties:

| Variable                             | Hex         | Usage                                                                        |
| ------------------------------------ | ----------- | ---------------------------------------------------------------------------- |
| `--color-theme` / `--color-theme-bg` | `#14120b`   | Page background, header background                                           |
| `--text-color`                       | `#edecec`   | Primary text, buttons, borders                                               |
| `--text-color-sec`                   | `#edecec99` | Secondary/muted text (e.g. testimonials, dates)                              |
| `--secondary-color`                  | `#1b1913`   | Cards, logo garden containers, feature/testimonial/use-case/changelog blocks |
| `--color-accent`                     | `#f54e00`   | "Learn more" and accent links                                                |

---

## Project Structure

```
cursor-landing-page-clone/
├── index.html          # Single-page markup
├── style.css           # All styles (layout, typography, colors)
├── README.md           # This file
└── assets/
    ├── logo.svg
    ├── favicon.png
    ├── hero-section.png
    ├── feature-1.png, feature-2.png, feature-3.png
    ├── use-case-1.png, use-case-2.png, use-case-3.png
    ├── team-photo.webp
    └── *-avatar.webp   # Testimonial avatars
```

---

## Screenshots

![Cursor landing page clone - full page](./assets/screenshots/homepage.png)

---

## How to Run

1. Clone or download the repo.
2. Open `index.html` in a browser, or serve the folder with a local server (e.g. `npx serve .` or VS Code Live Server).

No build step or dependencies required.

---

## Tech Stack

- **HTML5** – Semantic sections, links, and buttons.
- **CSS3** – Custom properties, Flexbox, Grid, sticky header, responsive-friendly layout.
- **Google Fonts** – Carrois Gothic.

---

## License

This is a learning/portfolio clone. Cursor branding and content belong to Cursor. Use only for personal/educational purposes.
