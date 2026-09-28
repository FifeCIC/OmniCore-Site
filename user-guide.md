---
layout: default
title: "User Guide"
url: /user-guide/
permalink: /user-guide/
---

<div class="page-header">
  <h1>User Guide</h1>
  <p>Everything you need to get started with OmniCore</p>
</div>

## What's Inside

| Tool | Description |
|------|-------------|
| **GT05 Ship Database** | Full ship roster with filters, sortable columns, expandable specs, and a dossier modal with official video |
| **HC05 Peripheral Configuration** | Load an XML profile, visualize HOTAS/KBM bindings, right-click to reassign inputs, and export back to XML |
| **VerseMail** | Submit contact transmissions or bug reports directly from the app (email + GitHub issue) |
| **AeroBook** | Social feed surface with in-app communication tools |

## Getting Started

OmniCore runs in your browser and installs as a PWA. No account is required for
most features.

1. Open the [app](https://fifecic.github.io/StarCitizen-OmniCore/)
2. For HOTAS configuration: place your profile XML in the expected folder, then open HC05 → Peripheral Configuration
3. Right-click any binding row in HC05 to capture a new keyboard, mouse, or HOTAS input
4. Use the Ship Database to research vessels, filter by role, manufacturer, or size, and view pledge/aUEC pricing

> Some tools need the local desktop server. The hosted build runs in **demo mode**
> and says so on screen rather than failing silently.

## Key Routes

| Route | Page |
|-------|------|
| `/` | Dashboard |
| `/ship-database` | GT05 Ship Database |
| `/hotas-config` | HC05 Peripheral Configuration (HOTAS/KBM) |
| `/settings/hotas` | HOTAS input test lab |
| `/aerobook` | Social feed + VerseMail |

## Using it with another flight sim

The peripheral engine is not tied to Star Citizen — see
[/about/]({{ '/about/' | relative_url }}) for what that means and how to register
interest in another sim.

## Hosted Access

- **App**: [fifecic.github.io/StarCitizen-OmniCore](https://fifecic.github.io/StarCitizen-OmniCore/)
- **Source**: [github.com/FifeCIC/StarCitizen-OmniCore](https://github.com/FifeCIC/StarCitizen-OmniCore)
