---
layout: default
title: "Home"
url: /
---

<div class="hero-section">
  <h1>OmniCore</h1>
  <p class="tagline">Citizen Operations &amp; Intelligence Network</p>
  <p class="subtitle">A companion hub for Star Citizen — ship intelligence, peripheral configuration, and in-game tooling in one MobiGlass-inspired interface.</p>
  <p><a class="card-link" href="https://fifecic.github.io/StarCitizen-OmniCore/">Open the app &rarr;</a></p>
</div>

---

## Built for Star Citizen — not limited to it

OmniCore's peripheral layer is **not Star Citizen-specific**. It reads and writes
bindings through an XML profile, and the parts that do the real work are generic to
any title that lets you bind a HOTAS, yoke or pedal set:

- **Device-aware upsert** — assigning a keyboard key never clobbers an existing HOTAS rebind for the same action
- **Duplicate-binding conflict detection**
- **Live input capture** through the browser Gamepad API

Today the app ships Star Citizen profiles, ship data and in-game tooling. The
configuration engine underneath does not care which sim it is talking to.

| Candidate | Why it fits |
|---|---|
| **Star Citizen / Squadron 42** | Supported today |
| **DCS World** | Deep, hand-edited binding files — the pain is well documented |
| **Elite Dangerous** | Large HOTAS community; bindings are plain, editable files |
| **Microsoft Flight Simulator** | Huge peripheral ecosystem and complex control profiles |
| **X-Plane** | Established community of custom binding setups |
| **IL-2 Sturmovik** | Enthusiast sim crowd, heavy HOTAS use |
| **Anything else with editable bindings** | If the sim exposes its bindings, the engine has something to work with |

> **Want it for another sim?** Say which sim and which hardware —
> [open a discussion](https://github.com/FifeCIC/StarCitizen-OmniCore/discussions)
> or [file an issue](https://github.com/FifeCIC/StarCitizen-OmniCore/issues).
> Interest is what decides what gets built next.

Supporting a second sim is a real piece of work — it needs a profile-format adapter
and a per-sim data set, not a config flag. The table is a shortlist of what would
make sense, not a roadmap promise.

---

## What's Inside

<div class="card-grid">
  <div class="card">
    <div class="card-icon">🛸</div>
    <h3>GT05 Ship Database</h3>
    <p>Full ship roster with filters, sortable columns, expandable specs, and a dossier modal with official video.</p>
    <a class="card-link" href="{{ '/user-guide/' | relative_url }}">Learn more &rarr;</a>
  </div>
  <div class="card">
    <div class="card-icon">🎮</div>
    <h3>HC05 Peripheral Configuration</h3>
    <p>Load an XML profile, visualize HOTAS/KBM bindings, reassign inputs, and export back to XML.</p>
    <a class="card-link" href="{{ '/user-guide/' | relative_url }}">Learn more &rarr;</a>
  </div>
  <div class="card">
    <div class="card-icon">📡</div>
    <h3>VerseMail</h3>
    <p>Submit contact transmissions or bug reports directly from the app.</p>
    <a class="card-link" href="{{ '/support/' | relative_url }}">Get in touch &rarr;</a>
  </div>
  <div class="card">
    <div class="card-icon">📖</div>
    <h3>Developer Docs</h3>
    <p>Architecture, APIs, and internal documentation for contributors.</p>
    <a class="card-link" href="{{ '/developer-guide/' | relative_url }}">Read docs &rarr;</a>
  </div>
</div>

---

## Disclaimer

OmniCore is a fan-made project. Star Citizen® is a registered trademark of Cloud
Imperium Rights LLC. Not affiliated with or endorsed by Cloud Imperium Games.
