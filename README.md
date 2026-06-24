# GEO Snapshot — Site

Static landing page for [GEO Snapshot](https://egiraldmu1795.github.io/geo-snapshot/).

## Files

- `index.html` — self-contained sales page (Tailwind v4 via CDN)
- `.nojekyll` — disables Jekyll processing on GitHub Pages
- `og.png` — social preview image (TODO: add before going live)

## Deploy

Push this directory to the `gh-pages` branch (or configure GitHub Pages to serve from `main` / `docs`).

```bash
# From repo root — example with gh-pages branch
git subtree push --prefix business/geo-snapshot/site origin gh-pages
```

## TODO

- Add `og.png` (1200×630 social preview)
- Replace `mailto:` CTAs with a real booking/checkout link once Stripe or Cal.com is wired up
  (search for `<!-- TODO: booking/checkout link -->` in index.html)
