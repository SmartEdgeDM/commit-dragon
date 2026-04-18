# Changelog

All notable changes to Commit Dragon are documented here.

---

## [1.6.0] — 2026-04-17

### Added
- `CONTRIBUTING.md` — guide for contributors including PR workflow, code style, and changelog instructions
- `.github/ISSUE_TEMPLATE.md` — structured bug report template
- Updated `README.md` — dragon mood system added to features list
- Updated `README.md` — full dragon mood table with all 5 moods, days, and descriptions
- Updated `README.md` — contributing section and full file tree
- Updated `social-preview.png` — larger, more readable fonts throughout

---

## [1.5.0] — 2026-04-17

### Added
- Dragon mood system — dragon reacts based on days since last commit
  - 😄 **Happy** — coded today, dragon is thriving
  - 😊 **Content** — coded yesterday, still going strong
  - 😤 **Hungry** — 3+ days without commits, dragon wants code
  - 😩 **Starving** — 7+ days, dragon is fading
  - 😴 **Dormant** — 14+ days, dragon has gone to sleep
- Mood banner displayed below the egg with label and description
- Egg shell tint changes per mood
- Dragon animation changes when hungry or dormant
- Descending 8-bit sound plays when dragon is hungry or starving

---

## [1.4.0] — 2026-04-17

### Added
- SmartEdge brand colors — Royal Azure Blue `#0056B3` with Cyber Lime `#CCFF00` accents
- Lime XP pips with glow effect on the tamagotchi screen
- Brand-colored calendar heatmap (blue → lime gradient)
- SmartEdge-themed share card with navy background and lime accents
- Updated favicon to blue egg with lime dashed pattern

---

## [1.3.0] — 2026-04-17

### Added
- 8-bit sound effects via Web Audio API — no extra files needed
  - 🍖 Feed: happy ascending 4-note chirp
  - ★ Play: bouncy playful arpeggio
  - ⟳ Sync: quick two-tone blip
  - 🥚 Summon: egg hatch chime
  - ✨ Evolution: full 7-note fanfare with sparkle tones
- Sound on/off toggle on the setup screen

---

## [1.2.0] — 2026-04-17

### Added
- 🔥 Commit fire calendar — 14-week heatmap with fire heat colors
- Share card — downloadable PNG of your dragon's current stage
- Evolution animation — egg shell pulses with glow when levelling up
- Dragon egg favicon embedded as SVG data URI
- `og:image`, `og:title`, `og:description` meta tags for social sharing
- SmartEdge Marketing footer link
- MIT License

---

## [1.1.0] — 2026-04-17

### Added
- Tamagotchi-style egg shell with working Feed, Sync, and Play buttons
- Screen messages appear inline on the tamagotchi display
- `commit.pet` branding on egg shell
- Auto-loads username on page open
- `README.md` with screenshot, feature list, and Buy Me a Coffee badge
- `.github/FUNDING.yml` — Buy Me a Coffee sponsor link

---

## [1.0.0] — 2026-04-17

### Initial Release
- Digital pet dragon that evolves based on GitHub public commit activity
- 5 evolution stages: 🥚 Egg → 🐣 Hatchling → 🦎 Wyrmling → 🐲 Drake → 🐉 Elder Dragon
- Live GitHub API integration — no login required
- Dragon vitals: streak, activity, and power bars
- Recent commit feed with repo names, messages, and timestamps
- Built with zero dependencies — pure HTML, CSS & JavaScript

---

Made with 💜 by [SmartEdge Marketing](https://SmartEdgeDM.com)
