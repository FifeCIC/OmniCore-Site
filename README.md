# OmniCore Website

Marketing site and guides for OmniCore, published with GitHub Pages at
**https://fifecic.github.io/OmniCore-Site/**

The app itself is published separately at
**https://fifecic.github.io/StarCitizen-OmniCore/** (repo:
[FifeCIC/StarCitizen-OmniCore](https://github.com/FifeCIC/StarCitizen-OmniCore)).

## Why two repositories

GitHub Pages serves **one site per repository**, and the app repo already publishes
the React PWA at its root. This repo holds only the marketing pages and guides, so
the two can be edited, built and deployed independently.

Before this split the Jekyll pages sat in the app repo unused — the app's Pages
workflow publishes `dist/`, so nothing ever served them, and `/about`,
`/user-guide`, `/support` and `/developer-guide/` all returned 404.

## Editing

- Pages are Markdown files at the repository root. `permalink` in the front matter
  sets the public URL (e.g. `permalink: /about/` → `/about/`).
- Navigation lives in `_config.yml` under `navigation`. A nav `url` must match a
  page's `url` for the active highlight to work.
- Styling: `assets/css/style.scss` imports `_sass/scifi-theme.scss`, which is shared
  with the app so the site and the PWA look like the same product.
- `_layouts/default.html` writes the `<title>`, canonical URL and Open Graph tags.
- Push to `main` publishes automatically via `.github/workflows/pages.yml`.

## Where the developer documentation lives

Technical guides stay in the app repo under `documentation/developers/` and are
linked from `/developer-guide/`. Deliberately **one copy, not two** — a duplicated
guide drifts, and only one of the copies gets the next correction.
