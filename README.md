# II (Intelligent Investing) — Prototype

Post-MVP dashboard prototype for Mogo's Intelligent Investing product.

## Pages

- **`index.html`** — Auto-redirects to the main dashboard.
- **`Unified Dashboard.html`** — Main dashboard. Open Questions, Core (Managed), Active (Self-Directed).
- **`Open Questions.html`** — Dedicated Open Questions detail screen.
- **`Performance Dashboard.html`** — Performance vs S&P 500 analysis.
- **`Open Positions.html` / `Closed Positions.html` / `Benchmark.html`** — Performance Dashboard sub-pages.

## Design system

Built against:
- `Doctrine/Mogo Design Philosophy.md`
- `Doctrine/Style_Design.md`

Severe brand posture. Grayscale-dominant, system tokens only, no decorative color, sentence/Title Case per audit.

## Local preview

Open `index.html` in a browser. Designed for mobile (393 × 852 viewport).

## Status

Prototype — link markup in place but most navigation intentionally inert until target pages are wired. Links with `data-active="true"` navigate; others preventDefault.

Active links:
- Open Questions summary → Open Questions.html
- Performance vs S&P → Performance Dashboard.html
- Performance Dashboard back arrow → Unified Dashboard.html

## Deploy

Static site — no build step. Deploy any way you like (GitHub Pages, Netlify Drop, etc.). The folder is self-contained.
