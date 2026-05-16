# Chanjuan Jin — Academic Website

Personal academic website built with [PRISM](https://github.com/xyjoey/PRISM) — a modern academic homepage template powered by Next.js and Tailwind CSS.

## Setup

This site uses:
- **Node.js 22+** — Download from [nodejs.org](https://nodejs.org)
- **npm** — Included with Node.js

## Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

Visit `http://localhost:3000` to preview.

## Content Management

All content is managed in the `content/` directory:

- `config.toml` — Site configuration, author info, navigation
- `about.toml` — Homepage sections
- `bio.md` — About me content
- `news.toml` — News items
- `publications.bib` — Publications in BibTeX format
- `cv.md` — CV content

## Deployment

This site automatically deploys to GitHub Pages via GitHub Actions when pushing to the `master` branch.

---

Built with [PRISM](https://github.com/xyjoey/PRISM) · MIT License
