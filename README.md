[README.md](https://github.com/user-attachments/files/25699820/README.md)
# 🚀 Far Reach

> *A single-file, browser-based 4X strategy game spanning five technological eras — from medieval castles to interstellar colonisation.*

---

## What is Far Reach?

Far Reach is a turn-based hex-grid strategy game in the tradition of Civilization, playable entirely in the browser with no installation, no server, and no dependencies. Build cities, research technologies, train armies, forge or break diplomatic alliances, and race your rivals to the stars — all in a single self-contained HTML file.

The game supports 1–4 civilisations across three planets (Earth, Moon, Mars), five difficulty levels, four unique factions, and a full suite of late-game wonders and special units. Sessions typically run 30–90 minutes.

---

## How to Play

### Getting Started

Open `farreach.html` in any modern browser. No server needed — just double-click the file or drag it into Chrome, Firefox, or Safari.

On the welcome screen, pick your faction from the strip at the bottom (hover or tap for details), then choose your opponents or hit **Quick Start** for a random setup. The game supports 1–3 AI opponents.

### Core Loop

Each turn you:
1. **Move and attack** with your units on the hex map
2. **Build units** at your cities
3. **Research technologies** from the sidebar Tech tab
4. **Manage diplomacy** with rival civilisations
5. Press **End Turn** — the AI takes its turn, then you go again

### Winning

There are four ways to win:

| Victory | Condition |
|---|---|
| 🏆 **Domination** | Eliminate all rival civilisations |
| 🚀 **Exodus** | Launch your Exodus Ship through the Black Hole |
| 🌌 **Colonisation** | Establish colonies on all three planets |
| ⏱️ **Score** | Highest score when the turn limit is reached |

### Cities

Cities level up as their population grows, producing more income per turn. Each city can be specialised with one of four buildings:

- 🏺 **Foundry** — units cost 1 less credit to build
- 💧 **Garrison** — city defence and HP regeneration
- 🔬 **Granary** — +1 credit income per turn
- 🧊 **Academy** — tech research costs 10% less

Your **HQ** (starting city) has a built-in defence tower that fires on adjacent attackers. Lose your HQ and you lose the game.

### Units

Nineteen unit types spanning all five eras:

| Era | Units |
|---|---|
| Medieval | Warrior, Archer, Knight, Catapult |
| Industrial | Rifleman, Artillery, Engineer, Settler |
| Atomic | Tank, Jet Fighter |
| Space | Psychic, Astronaut, Laser Trooper, AI Robot, Colony Vehicle, ICBM |
| Interstellar | Exodus Ship, Leviathan *(Benevolent only)* |

Units earn XP through combat, ranking up through **Seasoned → Veteran → Elite** — each rank adds stats and a visual badge.

**Settlers** found new outpost cities on unclaimed terrain. **Engineers** repair damaged cities. **ICBMs** deal area splash damage across the map. The **Leviathan** is a faction-exclusive titan that deals triple damage when your Wrath meter is maxed.

### Technologies

55 technologies spread across five eras unlock new units, buildings, wonders, and passive bonuses. The tech tree is visible in the sidebar **Tech** tab (desktop) or via the ⚗️ FAB button (mobile).

### Diplomacy

Manage relations with each AI civilisation on a scale from −100 (hostile) to +100 (allied). Available from the **Diplo** tab:

- Propose ceasefire / declare war
- Offer tribute or gift credits
- Negotiate open borders
- Establish trade deals for ongoing income

AI personalities respond based on their archetype — a Berserker rarely accepts peace; a Builder may trade readily.

### Wonders

Eleven wonders, each buildable once per game — first to build it claims it permanently:

| Wonder | Era | Effect |
|---|---|---|
| 🗼 Great Library | Medieval | +3 to all tech research |
| 🏯 Iron Citadel | Medieval | All cities +5 max HP and faster regeneration |
| 🏛️ Colosseum | Medieval | All units +2 ATK and +4 max HP |
| 🌐 Global Network | Industrial | Reveals entire map; +1 income per city per turn |
| 🌊 Tidal Engine | Industrial | +2 income per ocean/wetland tile adjacent to cities |
| ⚡ Arc Reactor | Space | +4 income per turn; units cost 15% less |
| 🛡️ Shield Array | Space | All units +2 DEF permanently |
| 🛰️ Orbital Cannon | Space | Fire a targeted orbital strike once per turn |
| 🧬 Genesis Lab | Interstellar | Cities auto-heal +3 HP/turn; units regen +2 HP/turn |
| 🌀 Warp Gate | Interstellar | Teleport any unit to any owned city once per turn |
| 🌑 Dark Forge | Interstellar | All units +3 ATK and +3 DEF permanently |

### Random Events

Ten random events fire periodically, from helpful (Desert Traders, Supply Cache, Alien Ruin) to destructive (Earthquake, Plague, Meteor Strike, Solar Flare). Most offer a choice of responses with different risk/reward trade-offs.

---

## Factions

| Faction | Flavour | Special Ability |
|---|---|---|
| 🚀 **Apex Ventures** | Private tech empire | All tech costs −20%; rockets and colony ships −2 credits |
| ☭ **The Collective** | Vast state machine | Units cost −1; cities spawn a free unit on population cap |
| 👽 **The Greys** | Ancient alien visitors | Start in Atomic era; traverse ocean and mountain tiles; Psychic units disable enemies for 1 turn |
| 🌊 **The Benevolent** | Ocean-born aliens | Elite small army; Leviathan unlocked when attacked; Leviathan deals 3× damage at max wrath |

---

## Difficulty Levels

| Level | Description | Key Modifiers |
|---|---|---|
| 🥔 Potato | Harmless | 0.6× damage, 55% blunder chance |
| 😴 Easy | Forgiving | 0.85× damage, occasional mistakes |
| ⚔️ Normal | Competent | Standard values |
| 💀 Hard | Relentless | Fog cheat, siege coordination, ICBM strikes, wonder priority, threat reaction |
| 🚀 Elon Mode | Ruthless | +6 income bonus, 1.45× damage, bonus starting techs, taunts, all Hard behaviours |

Hard and Elon Mode AIs coordinate multi-unit siege assaults before attacking cities, build and fire ICBMs at your HQ, aggressively claim high-value wonders, and immediately prioritise destroying your Exodus Ship if you build one.

---

## Scenarios

Three hand-crafted scenarios with fixed starting conditions:

- ⚔️ **Last Stand** — Your empire is on the brink. Three rivals encircle you. Survive and turn the tide.
- 🚀 **Space Race** — All players start in the Space era. First to launch the Exodus Ship wins.
- 🌱 **Fresh World** — A blank planet with no existing cities. Settle everything from nothing.

---

## Other Features

- **Daily Challenge** — A fixed-seed game that resets each day. Local streaks tracked.
- **Hall of Fame** — Top scores saved to local storage with faction and turn count.
- **Achievements** — Nine medals for feats like building a Wonder, triggering the Leviathan, and winning via Exodus.
- **Fog of War** — Black shroud that lifts as your units explore; enemies hidden until spotted.
- **Procedural Music** — Ambient generative soundtrack, unique per planet.
- **Sound Effects** — 16 SFX covering combat, diplomacy, era advance, wonder construction, unit loss, and city capture.
- **Save / Load** — Full game state serialised to local storage via the ☰ menu.
- **Multi-planet** — Unlock Moon and Mars by researching Moonbase and Mars Base; each runs as its own simultaneous hex map.
- **Mobile Support** — Full touch support: bottom sheet unit panel, FAB buttons for Tech/Diplo/Wonders, pinch-to-zoom, and safe area insets for notched devices.

---

## How to Run / Deploy

### Locally

```
open farreach.html
```

Or drag `farreach.html` directly into your browser. No build step, no dependencies.

### As a hosted page

Upload the single file to any static host:

- **GitHub Pages** — Drop `farreach.html` in your repo root or `/docs`, rename to `index.html`, enable Pages in settings
- **Netlify** — Drag the file into [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — Add `farreach.html` as `index.html` in a new project
- **Any web server** — It's one file, serve it as-is

The game stores all data in the browser's `localStorage` under the key prefix `farreach_`. Clearing site data resets scores, saves, and streaks.

### Requirements

- Any modern browser: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- JavaScript enabled
- No internet connection required after initial load (Orbitron and Exo 2 fonts load from Google Fonts on first open; the game runs fully offline after that)

---

## Technical Notes

Far Reach is a deliberate single-file constraint project — the entire game lives in one HTML file with no external dependencies, no build pipeline, and no framework.

- **Rendering** — Two stacked `<canvas>` elements: one for the hex map and terrain, one for particle FX and projectiles
- **Hex grid** — Offset coordinate system with BFS pathfinding for both AI movement and player range highlighting
- **AI** — Per-turn `doSingleAI()` driven by personality archetypes (Rusher, Builder, Tactician, Berserker, Researcher) with difficulty modifiers and Hard/Elon coordination behaviours layered on top
- **Audio** — Fully procedural synthesis via Web Audio API (`AudioContext`); zero audio files
- **Persistence** — `localStorage` for save/load, leaderboard, achievements, and daily challenge state
- **Size** — ~335 KB single HTML file; all logic, styles, and assets inline
- **Mobile** — `env(safe-area-inset-*)` for notch/Dynamic Island devices, `touch-action:manipulation` on all interactive elements, `dvh` units for dynamic viewport height

---

## Roadmap

- [ ] Multiplayer — hot-seat or async pass-and-play
- [ ] Procedural planet generation
- [ ] Additional factions
- [ ] Unit promotion choice trees (rather than automatic rank-up)
- [ ] Formal alliance and non-aggression pact system
- [ ] Map editor / custom scenario creator
- [ ] More Interstellar-era content and wonders
- [ ] Persistent campaign mode across multiple sessions

---

## Credits

**Design & development** — Built across 10 sessions of iterative human–AI collaboration.

**Inspired by** — Sid Meier's Civilization series and The Battle of Polytopia.

**Fonts** — [Orbitron](https://fonts.google.com/specimen/Orbitron) and [Exo 2](https://fonts.google.com/specimen/Exo+2) via Google Fonts (SIL Open Font License).

**Audio** — All sound and music generated procedurally at runtime via the Web Audio API. No audio files were used.

---

*The single HTML file is the source. Read it, fork it, mod it.*
