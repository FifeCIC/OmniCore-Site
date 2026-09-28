---
layout: default
title: "About"
url: /about/
permalink: /about/
---

<div class="page-header">
  <h1>About</h1>
  <p>The story behind OmniCore</p>
</div>

## The Project

OmniCore is a fan-made Star Citizen companion hub — a PWA combining ship
intelligence, peripheral configuration, and in-game tooling in one
MobiGlass-inspired interface.

It began with a specific irritation: configuring a HOTAS for Star Citizen means
editing the game's XML profile by hand, and most sims handle this badly. OmniCore
edits that file directly, backs profiles up, and captures new bindings live from
the stick rather than asking you to type key names into a text editor.

From there the ambition widened into a companion hub — ship data, game settings,
media, and tooling around the parts of the game that official tools do not cover.

## Built for Star Citizen, not limited to it

The peripheral layer is deliberately **game-agnostic**. Device-aware upsert (so one
device's binding cannot clobber another's), duplicate-binding conflict detection, and
live Gamepad API capture are all independent of which sim is reading the file.

That means OmniCore could be adapted for other flight sims — **DCS World**, **Elite
Dangerous**, **Microsoft Flight Simulator**, **X-Plane**, **IL-2 Sturmovik**, or
anything else that exposes editable bindings. Doing so needs a profile-format adapter
and a per-sim data set, so it is a genuine piece of work rather than a switch.

**If you fly a sim that is not Star Citizen and want a proper bindings editor for it,
say so.** Interest is what decides what gets built next —
[open a discussion](https://github.com/FifeCIC/StarCitizen-OmniCore/discussions) or
[file an issue](https://github.com/FifeCIC/StarCitizen-OmniCore/issues) with the sim
and the hardware you use.

## The Developer

OmniCore is built by **LOLinDark** — a Star Citizen backer since 2013, flying with a
Logitech/Saitek X52 and an interest in the tools that official clients never ship.

- [GitHub](https://github.com/LOLinDark)
- [RSI Profile](https://robertsspaceindustries.com/citizens/LOLinDark)

OmniCore is developed under the [FifeCIC](https://github.com/FifeCIC) organisation.

---

## Disclaimer

OmniCore is a fan-made project. Star Citizen® is a registered trademark of Cloud
Imperium Rights LLC. This is a non-commercial fan project, made under the Star
Citizen Fan Kit terms. Not affiliated with or endorsed by Cloud Imperium Games.
