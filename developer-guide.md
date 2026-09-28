---
layout: default
title: "Developer Guide"
url: /developer-guide/
permalink: /developer-guide/
---

<div class="page-header">
  <h1>Developer Guide</h1>
  <p>Architecture, APIs, and internal documentation for contributors</p>
</div>

## Quick Start

```bash
git clone https://github.com/FifeCIC/StarCitizen-OmniCore.git
cd StarCitizen-OmniCore
npm install        # install dependencies
npm run dev        # frontend on :4242
npm run server     # backend on :3001
```

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI Framework | React 18 + Vite |
| Component Library | Mantine 8 |
| Sci-Fi Visual Layer | Arwes 1.0.0-next |
| State | Zustand + TanStack Query |
| Backend | Express 5 |
| AI | Google Gemini + AWS Bedrock |
| PWA | manifest.json + service worker |

## Documentation

The technical guides live in the app repository — **one copy, not two**, so they
cannot drift from the code:

<ul class="doc-list">
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/DEVELOPER-REFERENCE.md">Developer Reference</a>
    <div class="doc-desc">Dev tag system, tech stack, project structure, Arwes integration, colour palette, backend API</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/HOTAS-CONFIG-GUIDE.md">HOTAS Configuration Guide</a>
    <div class="doc-desc">Keybinding system architecture, data model, device integration, and usage instructions</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/HOTAS-ADVANCED-USER-MODE.md">HOTAS Advanced User Mode</a>
    <div class="doc-desc">Advanced rebinding workflow and multi-mode controller support</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/AEROBOOK-GUIDE.md">Aerobook Guide</a>
    <div class="doc-desc">Verse media gallery implementation, video player, rotation system, and content curation</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/API-INTEGRATION.md">API Integration</a>
    <div class="doc-desc">Star Citizen API, Gemini, AWS Bedrock, media providers, API SDK ecosystem</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/MEDIA-LIBRARY-GUIDE.md">Media Library Guide</a>
    <div class="doc-desc">Centralised asset management, hero containers, dashboard images, YouTube integration</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/CONTENT-MARKERS-GUIDE.md">Content Markers Guide</a>
    <div class="doc-desc">Visual system for tracking placeholder content, WIP items, and missing assets</div>
  </li>
  <li>
    <a href="https://github.com/FifeCIC/StarCitizen-OmniCore/blob/main/documentation/developers/SECURITY.md">Security Standards</a>
    <div class="doc-desc">OWASP compliance, security rules, audit history</div>
  </li>
</ul>

## Contributing

- `npm run lint` — eslint
- `npm run build:guard` — production build plus the bundle-budget check
- Push to `main` publishes the app to GitHub Pages via `.github/workflows/jekyll-gh-pages.yml`
  (the filename is historical — it builds the Vite app, not Jekyll)
