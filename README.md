[README (1).md](https://github.com/user-attachments/files/25728626/README.1.md)
# Far Reach

> *The Far Reach Accords collapsed in 2387. What was once a unified human expansion across three worlds fractured into competing powers — some born of Earth's old nations, others evolved entirely in the void. Now each empire charts its own course to the stars, or burns trying.*

A complete 4X strategy game in a single 393KB HTML file. No installation, no server, no dependencies. Open and play.

---

## Overview

Far Reach is a turn-based hex-grid strategy game in the tradition of Civilization and The Battle of Polytopia. Build cities, research technologies across five eras, command armies, negotiate diplomacy, construct Wonders of the World, and race across three planets to claim victory before your rivals do.

Everything — art, audio, AI, UI — is generated procedurally in a single self-contained HTML file. It works offline once loaded, runs on mobile and desktop, and requires no accounts or data collection.

**Quick facts:**
- 4 playable factions with unique abilities and colour skin unlocks
- 5 technology eras: ⚔️ Medieval → 🏭 Industrial → ☢️ Atomic → 🚀 Space Age → 🌌 Interstellar
- 3 planets: Earth, Moon, Mars
- 18 unit types, 11 Wonders, 26 technologies, 8 random events
- 5 AI difficulty levels including Elon Mode
- 4 victory conditions: Domination, Exodus, Colonisation, Score
- 8-mission Campaign + free Skirmish + Daily Challenge
- Commander progression system: 50 levels, 15 titles, 12 faction skins, 4 map sizes
- 12 achievements, 2 scenarios, Hall of Fame leaderboard
- Full touch support — designed for iPhone and Android

---

## How to Play

### Starting Out

Open `farreach.html` in any modern browser. The welcome screen offers three modes:

**⚔ Campaign** — Recommended for new players. Eight progressive missions that introduce one mechanic per mission, from basic combat all the way to the full game. Completing Campaign unlocks Elon Mode and all Skirmish features.

**🗺 Skirmish** — Full free play. Choose your faction, rivals, difficulty, and map size.

**📅 Daily Challenge** — A new fixed-seed game each day. Builds a streak and awards bonus Commander XP.

### The Core Loop

Each turn you move and attack with units, build new units at cities, manage your technology research, handle any diplomacy, and end your turn. The AI then responds. Repeat until a victory condition is met or the turn limit expires.

Cities generate credits each turn. Credits pay for units and buildings. Cities level up as population grows, unlocking stronger buildings and higher production caps. Fog of war limits what you can see until your units or cities reveal nearby tiles.

### Victory Conditions

| Condition | How |
|---|---|
| **Domination** | Capture every enemy HQ city |
| **Exodus** | Build the Exodus Ship and reach the Black Hole hex |
| **Colonisation** | Hold active cities on all three planets simultaneously |
| **Score** | Highest score when the turn limit expires |

---

## Factions

| Faction | Special Ability | Playstyle |
|---|---|---|
| 🚀 **Apex Ventures** | Tech costs −20%. Rockets and colony ships cost −2 credits | Fast research, early space era |
| ☭ **The Collective** | All units cost −1 credit. Free unit when a city hits population cap | Economic snowball, unit flooding |
| 👽 **The Greys** | Start in the Atomic era. Units traverse ocean and mountains. Psychic unit disables enemies | Aggressive early game, tactical flexibility |
| 🌊 **The Benevolent** | Elite starting army. Leviathan awakens when attacked. Deals 3× damage at maximum Wrath | Defensive, punishes aggression hard |

Each faction has four colour skins — a default plus three unlockable variants that come with Commander progression. Skins are purely cosmetic and change how your faction's units and cities are rendered on the map.

---

## Units (18)

| Era | Units |
|---|---|
| ⚔️ Medieval | Warrior, Archer, Knight, Catapult |
| 🏭 Industrial | Rifleman, Artillery, Engineer, Settler |
| ☢️ Atomic | Tank, Jet Fighter, Psychic |
| 🚀 Space Age | Astronaut, Laser Trooper, AI Robot, Colony Vehicle, Exodus Ship, ICBM |
| 🌌 Interstellar | Leviathan |

Units gain XP from combat and rank up through Seasoned → Veteran → Elite, increasing their stats. The **Engineer** builds Outposts (+3 defence bonus). The **Settler** founds new cities. The **ICBM** launches from near your HQ with massive area effect. The **Exodus Ship** is required for a non-domination victory. The **Leviathan** is the most powerful unit in the game — enormous health, area attacks, and faction-scaled damage when The Benevolent are at maximum Wrath.

---

## Technologies (26)

Technologies are researched with credits and unlock units, buildings, and special abilities. Most techs have prerequisites. Completing all techs in an era triggers an era advance.

**Era progression unlocks:**
- Industrial era: Artillery, tanks, steam-powered cities
- Atomic era: Nuclear weapons, jet fighters, radar
- Space Age: Rocketry, orbital mechanics, colony ships, Moon Base, Mars Base
- Interstellar: Warp Drive, Dark Energy, Exodus Drive, the Leviathan

Key strategic techs: **Moon Base** (required to reach the Moon), **Mars Base** (required to reach Mars), **Exodus Drive** (required to build the Exodus Ship), **Warp Drive** (enables the Warp Gate Wonder).

---

## Wonders (11)

Each Wonder can only be built once per game across all players. Racing to Wonders before your rivals is central to mid-game strategy.

| Wonder | Effect |
|---|---|
| 🗼 Great Library | All tech costs −3 credits |
| 🏯 Iron Citadel | All your cities gain +5 max HP and +2 defence |
| 🌐 Global Network | Reveals the entire map. Fog of war removed permanently |
| ⚡ Arc Reactor | All your cities generate +3 credits per turn |
| 🛡️ Shield Array | Your units gain +2 defence. Air defence intercepts enemy missiles |
| 🛰️ Orbital Cannon | Unlocks Orbital Targeting: one free long-range strike per turn |
| 🏛️ Colosseum | +2 population growth across all your cities |
| 🌊 Tidal Engine | Ocean tiles generate +1 credit. Your units traverse ocean freely |
| 🧬 Genesis Lab | Instantly colonises Moon and Mars with a starter city each |
| 🌀 Warp Gate | Teleport one unit per turn to any city you own |
| 🌑 Dark Forge | Unlocks the Leviathan for all factions. +3 attack to all your units |

---

## AI Difficulty

| Level | Description | Notes |
|---|---|---|
| 🥔 Potato | Harmless. Forgets what turn it is | 0.6× damage, 55% blunder chance |
| 😴 Easy | Tries its best. Bless its heart | 0.85× damage, occasional mistakes |
| ⚔️ Normal | Competent. Will punish mistakes | Balanced — a real challenge |
| 💀 Hard | Relentless. Adapts. Remembers everything | Fog cheat, siege coordination, ICBM usage, Wonder priority |
| 🚀 Elon Mode | Moves fast, breaks things, already on Mars | +6 income, 1.45× damage, 2× tech speed, taunts. Unlocks after completing Campaign |

Hard and Elon Mode AI uses coordinated siege groups, ICBM threat assessment, Wonder race priority scoring, retreat evaluation, and full fog-of-war cheating.

---

## Campaign (8 Missions)

Each mission introduces one new mechanic and gates it until the player is ready.

| # | Title | New Mechanic | Unlock Reward |
|---|---|---|---|
| 1 | First Contact | Combat only | Buildings & Economy |
| 2 | Growing Pains | Cities & income | Tech Tree |
| 3 | Age of Invention | Technology | Wonders |
| 4 | Monuments to Power | Wonders | Diplomacy |
| 5 | The Art of War and Peace | Diplomacy | Multi-planet travel |
| 6 | Beyond the Sky | Multi-planet | Full tech tree |
| 7 | Arms Race | Full tech + Hard AI | Full Skirmish |
| 8 | The Final Frontier | Everything, 3 rivals, Hard | Elon Mode |

Each mission has an opening briefing and a closing narrative. Progress is saved automatically.

---

## Commander Progression

XP accumulates across all game modes and persists between sessions.

**XP sources:**
- Win: +100 / Loss: +20
- Each turn survived: +2
- Each unit killed: +3
- Each wonder built: +15
- Each tech researched: +1
- Daily Challenge bonus: +50
- Campaign mission bonus: +75

**50 levels, 15 titles:** Recruit → Scout → Soldier → Veteran → Warlord → Tactician → Admiral → Sovereign → Architect → Legend → Immortal → Overlord → Dominator → Conqueror → Commander

**Unlocks by level:**

| Level | Unlock |
|---|---|
| 5 | Standard+ map (24×18) |
| 10 | First alternate skin for each faction |
| 15 | Large map (30×22) |
| 20 | Second alternate skin for each faction |
| 25 | Massive map (38×28) |
| 30–40 | Third and fourth alternate skins |

The Commander card is shown on the welcome screen and after every game, with a full XP breakdown showing exactly what you earned.

---

## Map Sizes

| Size | Grid | Approx. Session Length |
|---|---|---|
| Small | 18×14 | 30–60 min |
| Standard+ | 24×18 | 45–90 min |
| Large | 30×22 | 60–120 min |
| Massive | 38×28 | 90–180 min |

---

## Random Events (8)

Events fire periodically during play and require a choice. A modal overlay appears; after you choose, it dismisses and leaves a notification badge you can tap to review.

Earthquake, Plague Outbreak, Meteor Strike, Solar Flare, Desert Traders, Alien Ruin Found, Dust Storm, City Uprising.

---

## Achievements (12)

| Achievement | Condition |
|---|---|
| First Victory | Win any game |
| Lightning Commander | Win in 20 turns or fewer |
| Swift Campaign | Win in 35 turns or fewer |
| Total Dominator | Eliminate all rivals |
| Exodus Pioneer | Win via the Exodus Drive |
| Red Planet | Reach Mars |
| Moonwalker | Reach the Moon |
| Impenetrable | Win without losing a city |
| Warlord | Eliminate 10 enemy units in one game |
| Faster Than Elon | Win on Elon Mode |
| Wrath of the Deep | Win as The Benevolent at maximum Wrath |
| Daily Challenger | Win the Daily Challenge |

---

## Scenarios

**Last Stand** — Your empire is on the brink. Three rivals surround you. Survive and turn the tide.

**Space Race** — All factions start in the Space era with advanced tech. First to launch an Exodus Ship wins.

---

## Diplomacy

Relations between you and each AI are tracked on a −100 to +100 scale. They improve through peace agreements and trade; worsen through attacks, city captures, and broken ceasefires.

Available actions: Propose Ceasefire, Offer Tribute, Propose Trade Deal, Request Open Borders, Declare War.

Each faction has distinct personality lines for war declarations, wonder completions, losing positions, and peace agreements. Elon Mode has its own set of taunts.

---

## Audio

**Music** — Fully procedural ambient score built with the Web Audio API. Slow warm pad chords (3.2s per bar) using layered detuned oscillators. Three distinct chord palettes per planet: Earth (warm minor), Moon (open major), Mars (low dusty minor). Shifts between a spacious explore mode and a tense staccato combat mode dynamically during play. Zero audio files — everything generated at runtime.

**Sound Effects (18)** — move, attack, laser, build, research, capture, launch, event, victory, defeat, wrath, diplo, peace, war, wonder, fortify, unitLost, cityLost, era. Each uses layered synthesis: noise bursts for impacts, chord stacks for fanfares, simulated reverb echoes for big moments like era advance and wonder completion.

---

## Mobile Support

Far Reach is designed for phones and tablets. Specifically tested on iPhone Safari.

- Pinch-to-zoom and pan on the hex map
- Floating action buttons for Diplomacy and Wonders (bottom corners)
- Full-screen mode: hides Safari address bar via scroll trick + `position:fixed` body
- `env(safe-area-inset-*)` for notched devices
- `touch-action: manipulation` throughout — no 300ms tap delay
- `100dvh` for correct viewport height on mobile browsers
- All tap targets minimum 44×44px

---

## Running the Game

**Locally:** Download `farreach.html`, open in any browser. No build step.

**Hosted:** Drop on any static host — GitHub Pages, Netlify, itch.io. One file, zero config.

**Requirements:** Chrome 90+, Firefox 88+, Safari 14+, Edge 90+. JavaScript must be enabled.

---

## Data & Privacy

All data stays on your device. Nothing is transmitted anywhere.

localStorage keys used:

| Key | Contents |
|---|---|
| `farreach_save` | Current game save |
| `farreach_campaign` | Campaign mission progress |
| `farreach_commander` | XP, level, unlocked skins, map size preference |
| `farreach_lb` | Hall of Fame top scores |
| `farreach_achievements` | Achievement flags |
| `farreach_daily_*` | Daily challenge state and streak |

No accounts. No analytics. No ads. No network requests after initial load.

---

## Technical Architecture

- **Single HTML file** — ~393KB, zero runtime dependencies, zero build tooling
- **Rendering** — Two `<canvas>` elements: primary hex map + particle effects. All terrain, unit, city, and Wonder artwork drawn programmatically via Canvas 2D API. Zero image files
- **Tile caching** — All terrain tiles and unit sprites pre-rendered to `OffscreenCanvas` and cached. Fog-of-war variants included
- **Pathfinding** — BFS for unit movement range and AI target selection
- **AI system** — Five difficulty profiles × four personality archetypes (Tactician, Rusher, Builder, Expansionist). Hard/Elon adds fog cheating, coordinated siege groups, Wonder priority scoring, ICBM threat modelling, retreat evaluation
- **Audio** — Entirely procedural: `OscillatorNode`, `AudioBufferSourceNode`, `BiquadFilterNode`, `GainNode`. No audio files
- **Persistence** — localStorage only. No external calls of any kind
- **Mobile** — `env(safe-area-inset-*)`, `touch-action:manipulation`, `100dvh`, orientation lock on fullscreen, iOS address-bar-hide scroll trick
- **Commander skins** — Applied at runtime by overwriting `FACTIONS[id].color` and `.light` before each game initialises

---

## Roadmap

- Google Play via TWA wrapper
- iOS App Store via Capacitor
- Steam via Electron
- Async multiplayer
- Additional factions and planets
- Unit promotion choice trees
- Map editor

---

## Credits

Designed and built in a series of human–AI development sessions.

Inspired by the Civilization series (Firaxis) and The Battle of Polytopia (Midjiwan).

Fonts: Orbitron, Exo 2 — Google Fonts, SIL Open Font Licence.

All art and audio generated procedurally at runtime. No image files. No audio files.
