# Lilypad Logic

A field study in CSS flexbox — 24 plates.

Every frog wants the lilypad of its own colour. You never move a frog; you write
flexbox declarations on the pond, and the pond arranges them.

## What's in it

- **24 plates** covering `flex-direction`, `justify-content`, `align-items`,
  `align-self`, `order`, `flex-wrap`, `flex-flow` and `align-content`.
- **Live CSS** — declarations apply as you type, frogs hop to their new positions.
- **Plain-language hints** — missing colons, unknown properties, invalid values
  and near-miss typos are explained instead of silently ignored.
- **Field notes** per plate — the properties in play, with click-to-insert values.
- **Progress saved** to `localStorage`; a plate index lets you jump around.
- Day/night themes, reduced-motion support, works down to phone width.

Any declaration that lands every frog on its matching pad counts — there is
usually more than one way.

## Running it

Single self-contained file. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

Only external dependency is Google Fonts (Fraunces, Karla, JetBrains Mono).
Offline it falls back to system serif/sans/mono and still works.

## Deploying

Static site, no build step. Vercel serves `index.html` from the repo root:

```bash
npx vercel --prod
```
