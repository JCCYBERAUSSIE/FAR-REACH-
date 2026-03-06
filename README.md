[README.md](https://github.com/user-attachments/files/25784489/README.md)
# Far Reach

**A browser-based 4X strategy game of galactic conquest.**

Build cities, research technologies across five eras, train armies, forge alliances, and eliminate rival factions to claim the stars — all in a single HTML file that runs on any device.

---

## Quick Start

Open `farreach.html` in any modern browser. No installation, no server, no dependencies.

- **Skirmish** — jump straight into a freeplay game with your chosen faction, map size, and difficulty
- **Campaign** — eight story missions with specific objectives, briefings, and escalating challenge
- **Daily Challenge** — a fresh seeded map every 24 hours, same for every player worldwide

---

## Factions

| Faction | Identity | Playstyle |
|---|---|---|
| 🚀 **Apex Ventures** | Corporate empire, blue | Aggressive expansion, Colony Vehicle & Exodus Ship cost reduction |
| 🧠 **The Collective** | Hive mind, purple | Research specialists, unit production discounts |
| 👽 **The Greys** | Alien federation, green | Exclusive Drone and Mind Probe units, unique tech access |
| 🌊 **The Benevolent** | Ocean civilisation, teal | Tidecaller healer unit, ocean traversal advantage |

Each faction has unique starting bonuses, a roster of voice lines for key game events, and four unlockable cosmetic skins earned through Commander Progression.

---

## Tech Eras

Research advances your civilisation through five eras. Each era unlocks new units, buildings, and victory paths.

| Era | Theme | Key Unlocks |
|---|---|---|
| ⚔️ **Medieval** | Swords & castles | Warriors, Archers, Knights, Catapults |
| 🏭 **Industrial** | Steam & gunpowder | Riflemen, Artillery, Engineers, Ironclads |
| ☢️ **Atomic** | Nuclear & aviation | Tanks, Jet Fighters, ICBMs, Radar |
| 🚀 **Space Age** | Orbit & AI | Laser Troopers, AI Robots, Colony Vehicles |
| 🌌 **Interstellar** | Exodus | Exodus Ship, Leviathan, Warp Drive, Dark Energy |

### Research Queue

Technologies take real turns to complete — early techs take 1–2 turns, late-game technologies take 5–6 turns. Only one technology can be researched at a time. Academies and the Great Library wonder each reduce research time by 1 turn. Locked techs display their prerequisites inline.

**26 total technologies** across the five eras, with full prerequisite chains.

---

## Units

**25 military, civilian, and naval units** across all eras. All units are drawn as era-appropriate silhouettes in the style of classic 4X games.

### Standard Units (all factions)
Warrior · Archer · Knight · Catapult · Rifleman · Artillery · Engineer · Settler · Tank · Jet Fighter · Laser Trooper · AI Robot · Colony Vehicle · Exodus Ship · ICBM · Psychic · Astronaut

### Naval Units
Galley (ocean only) · Ironclad (bombards coastlines) · Dreadnought (twin turret, long range)

### Faction-Exclusive Units
- **Apex Ventures** — Apex Drone (quad-rotor, fast recon)
- **The Collective** — Commissar (grants +2 ATK aura to adjacent units)
- **The Greys** — Mind Probe (steals a random tech from an adjacent enemy city)
- **The Benevolent** — Tidecaller (heals 2 HP to all adjacent friendly units per turn)

### Monsters (neutral, hostile)
Wolf Pack · Troll · Dragon · Void Beast — found scattered on the map, attack nearby units, drop loot and XP on defeat.

### Unit Progression
Units earn XP through combat and level up through four ranks: Seasoned → Veteran → Elite. Three identical unit types can **fuse** into a single stat-boosted stack. Ranked units retain their bonuses permanently.

---

## Cities & Buildings

Cities grow from level 1 to 7. Their visual appearance evolves to match the current tech era:

- **Medieval** — stone curtain walls, corner towers, keep with battlements and flag
- **Industrial** — brick factories, 2–3 smokestacks, illuminated window rows
- **Atomic** — full city skyline, central skyscraper with spire and antenna
- **Space / Interstellar** — geodesic dome megacity, energy rings, platform with spires

### City Districts (one per city)
| District | Bonus |
|---|---|
| 🏭 Foundry | Unit training costs -1💎 |
| ⚔️ Garrison | Newly trained units start with 1 XP |
| 🌾 Granary | City heals +3 HP/turn |
| 🎓 Academy | Tech research time -1 turn |

### Outposts
Settlers can found **Outposts** — forward bases that give defending units +3 DEF and can train basic units (Warrior, Archer, Knight, Rifleman). A dirt **road** is automatically drawn between your HQ and each outpost, giving units that move through road tiles 2× movement speed.

---

## Wonders

**11 buildable wonders** — one per city, permanent empire-wide effects.

| Wonder | Era | Effect |
|---|---|---|
| 📚 Great Library | Medieval | All tech costs -3💎, research time -1 turn |
| 🏰 Iron Citadel | Medieval | All cities +10 max HP |
| 🏛️ Colosseum | Medieval | All units +2 ATK and +4 max HP permanently |
| 🌐 Global Network | Industrial | Full map reveal — no fog of war |
| ⚡ Arc Reactor | Industrial | +3💎 income per city per turn |
| 🌊 Tidal Engine | Industrial | +2💎 per ocean/wetland tile adjacent to your cities |
| 🛡️ Shield Array | Atomic | All units +2 DEF permanently |
| 🧬 Genesis Lab | Atomic | Cities auto-heal +3 HP/turn; units regen +2 HP extra per turn |
| 🛰️ Orbital Cannon | Space | Devastating strike anywhere on the map, once every 3 turns |
| 🌀 Warp Gate | Space | Teleport any unit to any owned city, once per turn |
| ⚒️ Dark Forge | Interstellar | All units +3 ATK and +3 DEF permanently |

---

## Random Events

**12 random events** fire throughout the game, each presenting three choices with real strategic consequences — from earthquakes and plagues to alien ruins and enemy defectors.

Earthquake · Plague Outbreak · Meteor Strike · Solar Flare · Desert Traders · Alien Ruin Found · Dust Storm · City Uprising · Comet Passing · Enemy Defector · Ancient Pathogen · Supply Cache

---

## Late-Game Crisis Events

Four major crises can strike after turn 45, forcing all factions to respond simultaneously.

| Crisis | Effect |
|---|---|
| 👾 **Alien Invasion** | Alien Swarm units spawn and attack for 8 turns |
| ☄️ **Meteorite Impact** | 5-turn countdown; impact destroys a 2-hex radius |
| 🦠 **The Great Pandemic** | Units without MEDICINE tech take 2 HP/turn for 6 turns |
| ☀️ **Solar Superstorm** | Research halted, ranged unit range halved for 4 turns |

---

## Diplomacy

Maintain long-term relations (-100 to +100) with every rival faction.

- **Peace Treaty** — end active wars; AI acceptance based on relations and personality
- **Open Borders** — grant mutual map traversal for 8 turns
- **Trade Deal** — pay a fee for +2💎/turn for 10 turns
- **Declare War** — drop relations, all factions are notified
- **Gift Credits** — improve relations directly

AI personalities (Rusher, Builder, Tactician, Berserker, Researcher) affect diplomacy acceptance rates and combat aggression.

---

## Victory Conditions

| Victory | Condition |
|---|---|
| **Domination** | Eliminate all rival cities and units across every unlocked planet |
| **Exodus** | Build an Exodus Ship and move it to the Black Hole hex |

---

## AI Difficulty

| Level | Description |
|---|---|
| 🥔 Potato | Passive, wanders randomly, frequent blunders |
| 😴 Easy | Gentle opponent, retreats early |
| ⚔️ Normal | Balanced play, moderate aggression |
| 💀 Hard | Fog-of-war awareness, coordinated multi-unit attacks, ICBM use |
| 🚀 Elon Mode | Maximum aggression, bonus start resources, multi-tech per turn, taunts you |

Hard and Elon AI respond dynamically to threats — attacking an AI city triggers a 4-turn rally, sending nearby units to defend.

---

## Planets & Map Sizes

Three planets unlock through Commander Progression: **Earth → Moon → Mars**, each with unique terrain, resources, and ambient music palettes.

| Map | Grid | Unlock Level | Estimated Length |
|---|---|---|---|
| Small | 18 × 14 | 1 | 30–60 min |
| Standard+ | 24 × 18 | 5 | 45–90 min |
| Large | 30 × 22 | 15 | 60–120 min |
| Massive | 38 × 28 | 25 | 90–180 min |

---

## Commander Progression

A persistent cross-session system that rewards continued play.

- **50 levels**, 15 titles from Scout to Galactic Overlord
- **XP** from wins, turns survived, units defeated, wonders built, techs researched, campaign missions, and daily challenges
- **16 cosmetic faction skins** — four per faction, unlocked at milestone levels
- **Map sizes** unlock at levels 5, 15, and 25

---

## Sound & Music

**18 sound effects** synthesised via Web Audio API, routed through a master dynamics compressor and warmth filter. Effects cover unit selection, movement, combat, construction, research, capture, diplomacy, era advance, crisis events, victory, and defeat.

**Adaptive music** uses layered ambient pad chords that switch between explore and combat modes in real time. Planet-specific palettes for Earth, Moon, and Mars.

---

## Controls

### Desktop
| Input | Action |
|---|---|
| Click unit | Select, show move range |
| Click green hex | Move selected unit |
| Click enemy in range | Attack |
| Click city | Open city panel |
| Right-click / click empty hex | Deselect |
| Scroll wheel | Zoom |
| Click + drag | Pan map |
| End Turn button | End your turn |

### Mobile
- Tap to select, move, and attack
- Pinch to zoom, drag to pan
- Bottom sheet for city and unit info
- Floating action buttons for tech, diplomacy, and wonders

---

## Technical Details

- **Single file** — `farreach.html` (~490 KB), no dependencies, no server required
- **Runs offline** — service worker enables PWA / offline play
- **PWA-ready** — installable to home screen on iOS and Android
- **Persistent save** — full game state written to localStorage
- **Daily Challenge** — deterministic seeded RNG ensures the same map worldwide each day
- **Version** — 1.0.0

### Browser Support
Chrome 90+, Safari 15+, Firefox 90+, Edge 90+. Requires Canvas 2D and Web Audio API.

---

## Roadmap

- Native app wrappers — iOS App Store / Google Play (pending monetisation decision)
- Additional planets
- Async multiplayer
- Steam via Electron wrapper

---

*Far Reach is independently developed. All rendering, audio, and generation runs entirely in-browser — no external assets, no analytics, no tracking.*
