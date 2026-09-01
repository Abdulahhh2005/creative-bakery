# Creative Bakery

A one-page bakery landing site: hero, product showcase, about section with stats, blog preview
and a contact block. Plain HTML and SCSS, BEM naming, no framework.

**Live demo:** pending — not deployed yet.

## What it does

- **Hero** with a call to action
- **What We Bake** — a grid of featured products
- **About Us** — company blurb with stat counters
- **Blog** preview section
- **Contact** block with social links
- **Theme switcher** — toggles an alternate colour palette across the page
- Smooth in-page scrolling, responsive down to mobile with no horizontal scroll

## Stack

HTML5 · SCSS (BEM naming, enforced by `.bemlintrc.json`) · vanilla JavaScript. No framework, no
client-side build tooling beyond `mate-scripts` for linting and deploy.

## Running it locally

```bash
git clone <repository-url>
cd creative-bakery
npm install
npm start
```

Other commands:

```bash
npm run lint    # style-format + format + mate-scripts lint — WRITES files
```

## How it is put together

Static markup in `src/index.html`, styles split into BEM blocks under `src/styles`, and a small
`src/scripts/main.js` handling the theme toggle. No client-side routing or state beyond that.
