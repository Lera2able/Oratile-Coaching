# Oratile Coaching

Premium one-page website for **Oratile Coaching**, a personal and leadership coaching practice based in eMalahleni, Mpumalanga, South Africa.

Tagline: **Grow your mind. Transform your life.**

## Overview

This project contains a polished editorial-style coaching website with:

- A premium navy-and-gold visual system
- A custom line-art hero emblem
- Responsive one-page layout
- A comparison page variant with a still portrait added to the About section
- Embedded motion and portrait assets

The site is designed as a canvas-ready project and also includes standalone HTML pages that can be previewed in a browser.

## Project Structure

```text
oratile-coaching-website/
├── assets/
│   ├── oratile-about-portrait.png
│   └── oratile-portrait-motion.mp4
├── pages/
│   ├── index.html
│   └── index-about-portrait.html
├── README.md
├── colors_and_type.css
├── oratile-coaching-website.design
└── orchestration-summary.json
```

## Key Files

- `oratile-coaching-website.design`
  Main design project entry used on the design canvas.

- `pages/index.html`
  Original one-page site version.

- `pages/index-about-portrait.html`
  Updated comparison version with the still portrait in the About section.

- `colors_and_type.css`
  Core brand colours, typography, and visual tokens for the site.

- `assets/oratile-portrait-motion.mp4`
  Motion asset used in the hero.

- `assets/oratile-about-portrait.png`
  Still portrait used in the About section of the updated page.

## Preview Options

### In the design canvas

Open `oratile-coaching-website.design` in the design canvas to view the project and compare page versions side by side.

### In a browser

From the project folder, start a simple local server and open either page:

```bash
python -m http.server 8000
```

Then visit:

- `http://localhost:8000/pages/index.html`
- `http://localhost:8000/pages/index-about-portrait.html`

## Design Notes

- Tone: editorial, elegant, warm, and grounded
- Primary colours: deep navy and warm gold
- Typography: serif-led display paired with clean body text
- Motion: subtle reveal animation with reduced-motion support
- Accessibility: responsive layout, visible focus states, and motion fallbacks

## Repository

GitHub repository:

`https://github.com/Lera2able/Oratile-Coaching.git`
