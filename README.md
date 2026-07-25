# coLoLrizer — Combat & Systems Designer

**Specialization:** Combat Systems, Boss Encounters, Ability Mechanics
**Experience:** No Name Games (Systems Designer, Oct 2024 – May 2025) + shipped solo/team projects + 1.5+ years independent portfolio work
**Location:** Remote (Ukraine)

Every system I build, I try to exploit first. I design boss fights and ability systems by playing against my own assumptions — checking dodge windows against real player stats, finding the exploit before a player would, and not calling a mechanic done until I've genuinely failed to break it.

---

## 🎮 Featured Work

### NO HIT! — Solo Boss Fight, Shipped in 4 Days
🎮 [Play it on CrazyGames](https://www.crazygames.com/preview/257a3540-822d-4ce8-ab83-57f2d0f22fde) Or [Watch the Fight](https://www.youtube.com/watch?v=7lJ2MaJblB4)

<p align="center">
  <a href="https://www.youtube.com/watch?v=7lJ2MaJblB4">
    <img src="https://github.com/user-attachments/assets/11b6c16e-ab1f-44cb-9624-a2cda9fad479" width="800">
  </a>
  <br>
  <sub>Gameplay preview may be loading.. — click to watch full video</sub>
</p>

Fully deterministic two-phase boss fight, designed and built solo for the CrazyGames × Construct Game Jam — first time ever using Construct 3.

**Key Features:**
- Every attack dodge-checked against actual player stats (movement speed, dash cooldown) — nothing can be beaten for free
- Predictive-targeting logic ported from an earlier Python prototype (Crimson Witch) into JavaScript
- Phase 2 keeps each attack's identity and visual language, but reworks its correct dodge — same theme, different solution, so player pattern-memory from Phase 1 doesn't transfer directly

**Technical Highlight:**
Diagnosed a Construct 3-specific bug where `Restart Layout` doesn't clear JS-side global state, and solved it with a reusable hide/disable-and-reset pattern instead of destroying objects.

[Full Case Study →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/NO%20HIT!%20case%20study.md)

---

### Crimson Witch — Boss Encounter Design
📺 [Watch 8-Minute Video Breakdown](https://youtu.be/bGkVlFrUSY4)

A simple resource idea — a limited potion pool the boss has to keep re-brewing — grew into a full encounter with world-level economic consequences.

**Key Features:**
- Potion brewing/resource-limit system with dual modes (self-buff vs. thrown hazards)
- Predictive targeting AI that tracks player velocity
- Player-like decision-making (heals at low HP, adapts behavior per phase)
- World economy loop: the boss's death reshapes NPC potion availability across the game world
- Modifier system: 5 difficulty toggles that upgrade both boss and loot

**Technical Implementation:**
- Python prototype with playable combat
- State machine AI for phases and combo attacks
- Weighted probability system for potion decisions

> Reviewed by a Senior Game Designer at Blizzard Entertainment: *"You've done a great job at breaking down the fight structure, describing the ramping threat, and designing a unique encounter... it's a strong theme."*

[Full Documentation →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/CrimsonWitch.md)

---

### Monolith — Technical Ability Design

An orbital combat ability that always chooses the biggest arc, never flies into the player's face, and stays stable under camera rotation.

**Problem-Solving Focus:**
- Quadrant-based space division (rotation-invariant, unlike an early 2-sector split that broke under camera rotation)
- Dual-tangent orbit entry/exit logic
- Phantom orbit fallback for cursor-inside-orbit edge cases
- Explicit state machine: `FALLING_INIT → GROUNDED → ENTER_ORBIT → ARCING → FLYING_TANGENT → CAPTURED`

[Full Technical Breakdown →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/Monolith.md)

---

### Telekinetic Class — Class Design

Complete custom class for Wynncraft MMO with 3 archetypes and a full ability tree, DPS-verified across 25+ builds.

**Design Scope:**
- 3 distinct archetypes (Defender, Elementalist, Mindbreaker), each with distinct resource mechanics
- Physics-based "Weight as a Weapon" tank identity for the Defender archetype
- Resource mechanics and ability synergies across archetypes
- JSON ability tree structure compatible with Wynnability tooling

[View Documentation →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/Telekinetic.md)

---

### Blightfall: Crimson Veil — Systems Design & Team Coordination
🎮 [Shipped on CurseForge](https://www.curseforge.com/hytale/mods/blightfall-crimson-veil)

Joined a 7–8 person volunteer team to design the core gameplay loop for a Hytale mod submitted to the CurseForge New Worlds Modding Contest (Mar–May 2026).

**Contributions:**
- Core gameplay loop, Crimson Escalation system, progression, and crafting economy
- Four design pillars introduced to stabilize scope after early "Idea Soup" creep
- Unofficial Vision Keeper / Lead Systems Designer role, coordinating team direction without formal production authority

This is a postmortem, not a success story — the shipped build diverged significantly from the design. Covers what went wrong, what shipped vs. designed, and lessons learned about scope, ownership, and documentation.

[Full Postmortem →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/Blightfall.md)

---

### Orbital Strike — Iterative Design Case Study

Evolution of one ability across three design contexts (fantasy → prototype → MMO-ready).

**Shows:**
- Terrain dependency analysis
- UX/balance trade-offs
- Platform-specific constraints (Wynncraft vs. Arhea)

[Read Case Study →](https://github.com/coLoLrizer/PORTFOLIO/blob/main/Orbital_Strike_Evolution.md)

---

## 💼 Professional Experience

**No Name Games — Systems Designer**
*Oct 2024 – May 2025 | Mobile Game Development (joined pre-rebrand, as White Deer)*
- Designed a full trick system for a mobile snowboard game: dozens of individual tricks across 5 rarity tiers (Common → Legendary), each with its own distinct QTE mechanic — single tap, timed hold, multi-directional swipe combos, balance-bar tracking, Osu-style circle rotation
- Built a systemic environmental modifier layer (Storm, Avalanche, Wind, Ice) that alters QTE difficulty and timing across the entire trick roster, rather than being hand-scripted per trick
- Designed a scalable progression system supporting 30+ unique mechanics without changes to core logic
- Authored technical design specs for QTE and input systems: timing rules, rotation logic, failure conditions
- Modeled soft→hard currency economy loops in Excel for stable progression pacing

---

## 🛠️ Skills & Expertise

**Core Competencies:**
- Combat & Encounter Design (boss fights, ability kits, combo systems)
- Systems Design (progression, itemization, build diversity)
- Prototyping (Python, JavaScript, functional demos)
- Technical Documentation (GDDs, ability sheets, technical specs)

**Design Philosophy:**
- Player agency and skill expression
- Design by breaking my own assumptions before they ship
- Systemic cohesion — encounters that leave a mark on the wider game world
- Risk/reward balance and counterplay

**Tools:**
- Python, JavaScript (Construct 3)
- GitHub, Markdown, Trello
- Excel / Google Sheets (economy modeling, balance)

---

## 🎯 What I'm Looking For

Remote Game Designer roles focused on:
- Combat systems and boss/encounter design
- Ability design and class mechanics
- Systems design and progression

**Open to:** Full-time positions, contract work, paid design tests

---

## 📫 Contact

**Email:** timurl.gamedev@gmail.com
**LinkedIn:** https://www.linkedin.com/in/timur-l-476966373/
**Portfolio:** https://github.com/coLoLrizer/PORTFOLIO

---

*Last updated: July 2026*
