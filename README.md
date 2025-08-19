# Aiotize Inc. Design System & Brand Assets

This repository hosts Aiotize Inc.'s design system, brand assets, and public documentation site. The visual language is inspired by the clean, minimal aesthetic of Perplexity while preserving Aiotize's display wordmark for `AI` and `AIOTIZE INC`.

## Quick Links

- Design tokens and themes: `aiotize/design-system/tokens`
- Core UI styles and components: `aiotize/design-system/{themes,components}`
- Brand assets (logo, fonts, palettes, templates): `aiotize/brand`
- Public site (auto-deployed): `docs/`

## Getting Started

1. Browse the live documentation site after the first successful deployment (GitHub Pages). It showcases tokens, components, and downloadable assets.
2. Update colors, spacing, typography, and motion via `aiotize/design-system/tokens/tokens.json`. CSS variables are generated in `tokens.css` for direct consumption.
3. Keep the `AI` and `AIOTIZE INC` display typeface when updating brand typography. Add the font files under `aiotize/brand/fonts/` and map them in `aiotize/brand/fonts/font.css`.

## Directory Overview

- `aiotize/design-system/` — Design tokens, themes (light/dark), and baseline components (button, card).
- `aiotize/brand/` — Logos, fonts, color palettes, templates, creative backgrounds, and layout grids.
- `docs/` — Static site used for GitHub Pages to preview the system and host downloads.

## Contributing

Open a pull request with clear descriptions and screenshots for visual changes. Follow conventional commits where possible.

## License

Unless otherwise noted inside a subfolder, assets and code in this repository are provided under the license in `LICENSE`.
