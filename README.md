# notequalsymbol.com

Tools to verify if two things are equal — or not. A nonsense website that interrogates sameness across text, color, numbers, dates, JSON, URLs, and more.

Live at [notequalsymbol.com](https://notequalsymbol.com)

## Features

- **Universal checker** — paste anything, auto-detects type and runs all applicable comparisons
- **Text** — exact, case-insensitive, whitespace-normalized, Unicode NFC
- **Color** — hex, RGB, HSL, named colors; accepts loose formats like `ff0000` or `(255, 0, 0)`
- **Number** — decimal, hex, binary, octal, with optional tolerance
- **Date** — ISO strings, timestamps, natural language
- **JSON** — deep structural equality, key order ignored
- **URL** — normalized protocol, host, sorted query params, trailing slashes

## Tech stack

- [Astro](https://astro.build) 6
- [Tailwind CSS](https://tailwindcss.com) 4
- Vanilla JS for all comparison logic (no framework)

## Getting started

### Prerequisites

- Node.js 22.12+
- [pnpm](https://pnpm.io)

### Commands

```bash
pnpm install   # install dependencies
pnpm dev       # start dev server at http://localhost:4321
pnpm build     # production build to dist/
pnpm preview   # preview production build
```

## Project structure

```
notequalsymbol.com/
├── src/
│   ├── pages/
│   │   └── index.astro    # single-page app
│   └── styles/
│       └── global.css     # design tokens + utilities
├── public/
│   ├── CNAME              # custom domain
│   └── favicon.svg
├── astro.config.mjs
└── .github/workflows/
    └── deploy.yml         # GitHub Pages CI/CD
```

## Deployment

Pushes to `main` or `master` trigger an automatic deploy to GitHub Pages via `.github/workflows/deploy.yml`.

1. Point DNS for `notequalsymbol.com` at GitHub Pages (A records or CNAME to your `*.github.io` host).
2. In the repo: **Settings → Pages → Source: GitHub Actions**.
3. Set the custom domain to `notequalsymbol.com` and enable HTTPS.

## License

Portfolio / demonstration project. Use freely with attribution.

## Credits

Built by [Claude](https://anthropic.com) (Anthropic) via [Cursor](https://cursor.com). This is a nonsense website — no guarantees on verdicts, vibes, or life choices.

Repository: [github.com/Paillat-dev/notequalsymbol.com](https://github.com/Paillat-dev/notequalsymbol.com)
