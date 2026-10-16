# Selected works — 2026

Three independent, responsive website concepts for a portfolio. All brands are fictional; these are demo projects, not commissioned client work.

- **MORI Coffee** — a specialty coffee shop: seasonal menu filters, demo table reservations and downloadable reservation details.
- **FORMA Objects** — a furniture and homeware store: six original SVG illustrations, search, categories, sorting, a persistent cart and downloadable demo order summaries.
- **ORBIT Studio** — a digital studio: project filters, an interactive demo estimate and a locally saved, downloadable project brief.

## Live websites

- [Gallery](https://nothing1212673-droid.github.io/portfolio-websites/)
- [MORI](https://nothing1212673-droid.github.io/portfolio-websites/mori/)
- [FORMA](https://nothing1212673-droid.github.io/portfolio-websites/forma/)
- [ORBIT](https://nothing1212673-droid.github.io/portfolio-websites/orbit/)

## Technology

HTML, CSS and JavaScript, with no dependencies or build step. Responsive layouts, accessible dialogs, keyboard navigation, reduced-motion support and local browser storage. System fonts. Each website is contained in its own index.html file.

All website copy, accessibility labels, notifications and generated downloads are in English. Prices remain in Ukrainian hryvnias (UAH); no currency conversion has been applied.

## Local preview

Run `node serve.mjs` and open http://127.0.0.1:4175/.

## GitHub Pages

Settings → Pages → Deploy from a branch → main → / (root).
The .nojekyll file disables Jekyll processing. Commits to main trigger an automatic GitHub Pages update.

## Editing

Colours and responsive rules are in each page’s style block; interactions are in its script block. MORI menu entries are in the menu array. FORMA products are in the products array. The ORBIT estimate is calculated by the calculate function.

## Demo limitations

All content is illustrative. Forms do not send messages, reservations do not book a real table, and the cart does not place a real order. Data is stored only in localStorage; if storage is blocked, the current interaction works in memory until the page is refreshed. Prices are examples, not commercial quotes. Pulse is a static UI concept, not a working application. User-entered text is preserved as entered.

## Images

FORMA objects and ORBIT thumbnails are original SVG/CSS illustrations. MORI photos and the FORMA interior photo are illustrative Unsplash images, loaded from images.unsplash.com and requiring an internet connection. They do not depict actual products, venues or commissioned projects for these fictional brands. Sources are listed in ASSETS.md.
