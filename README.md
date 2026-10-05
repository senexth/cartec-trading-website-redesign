# Cartec Trading — Website

Home page for Cartec Trading, built as a fully static site with [Astro](https://astro.build).

## Stack

- **Astro** — static output (`output: 'static'`), no server/SSR
- **Tailwind CSS v4** — via `@tailwindcss/vite`, with design tokens defined in `src/styles/global.css` (`@theme`)
- **React** — wired up via `@astrojs/react` for any future interactive islands (none of the current sections need client JS)
- **Plus Jakarta Sans** — self-hosted variable font via `@fontsource-variable`

## Getting started

```bash
pnpm install
pnpm dev       # start dev server
pnpm build     # build static output to dist/
pnpm preview   # preview the production build locally
```

## Project structure

```
src/
  components/   # one component per section (Header, Hero, VideoShowcase, SubDivisions, Clients, Partners, Footer)
  layouts/       # base HTML shell (Layout.astro)
  pages/         # index.astro assembles the home page from the components above
  styles/        # global.css — Tailwind v4 design tokens (@theme)
public/
  favicon.svg
```




