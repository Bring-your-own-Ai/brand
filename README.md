## Aiotize Inc. — Design System & Brand Assets

This repository stores Aiotize Inc.'s design system, brand assets, and ready‑to‑use templates. It is inspired by the visual language of Perplexity.ai while preserving Aiotize’s distinct `AI` and `AIOTIZE INC.` display marks.

### What’s inside
- `design-system/`: Design tokens (colors, spacing, typography, motion), component CSS, and theming.
- `brand/`: Logos, typefaces, color palettes, backgrounds, grids, and usage docs.
- `docs/`: A static preview site showcasing tokens and components.
- `templates/`: Simple HTML templates (hero, landing skeleton) using the design system.

### Quick start (no build tools required)
Open `docs/index.html` in your browser. It references the design tokens and components directly from the repo.

### Philosophy
- Keep the `AI` and `AIOTIZE INC.` display wordmark unique to Aiotize.
- Derive the rest of the system (layout, tone, gradients, controls) from a Perplexity‑like aesthetic: calm oceanic darks, clear contrast, elegant spacing, subtle borders, and smooth motion.

### Adding/Updating brand assets
- Place final vector logos in `brand/logos/` (keep provided filenames to avoid breaking links in docs).
- Add licensed font files to `brand/fonts/` and update the `@font-face` blocks in `design-system/tokens.css` and `brand/fonts/README.md`.
- If you update color tokens in `design-system/tokens.css`, the docs and templates will pick them up automatically.

### Legal & attribution
- Do not copy Perplexity.ai proprietary marks or copyrighted assets. This repository implements an original theme and tokens inspired by their public aesthetic.
- All original code in this repository is licensed MIT (see `LICENSE`). Your logos, fonts, and media remain your property under their respective licenses.