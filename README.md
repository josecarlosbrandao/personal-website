# Personal Website

Personal website for José Carlos Brandão, built with [Astro](https://astro.build), Tailwind CSS v4, and deployed to GitHub Pages.

**Live:** https://josecarlosbrandao.github.io/personal-website

## Project Structure

```text
src/
├── assets/          # Images (portrait, etc.)
├── components/      # Astro components (Hero, Header, Footer, ThemeToggle, etc.)
├── layouts/         # BaseLayout
├── pages/           # Routes: index, about, resume, linkedin
└── styles/          # Global CSS (Tailwind)
```

## Commands

| Command        | Action                                       |
| :------------- | :------------------------------------------- |
| `bun install`  | Install dependencies                         |
| `bun dev`      | Start dev server at `localhost:4321`         |
| `bun build`    | Build production site to `./dist/`           |
| `bun preview`  | Preview production build locally             |

## Tech Stack

- **Astro 6** — static site generator
- **Tailwind CSS 4** — styling via Vite plugin
- **@astrojs/sitemap** — automatic sitemap generation
- **GitHub Pages** — hosting (base path: `/personal-website`)

Requires **Node >= 22.12.0**.
