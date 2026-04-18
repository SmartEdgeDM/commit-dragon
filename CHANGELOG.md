# Changelog

All notable changes to Commit Dragon are documented here.

---

## [1.5.0] — 2026-04-17

### Added
- Dragon mood system — dragon reacts based on days since last commit
  - 😄 **Happy** — coded today, dragon is thriving
  - 😊 **Content** — coded yesterday, still going strong
  - 😤 **Hungry** — 3+ days without commits, dragon wants code
  - 😩 **Starving** — 7+ days, dragon is fading
  - 😴 **Dormant** — 14+ days, dragon has gone to sleep
- Mood banner displayed below the egg showing current mood, label and message
- Egg shell tint changes per mood (dims and desaturates the longer you neglect it)
- Dragon animation changes — wiggles anxiously when hungry, slow drift when dormant
- Screen message reflects current mood on load
- Descending 8-bit sound plays when dragon is hungry or starving

---

## [1.4.0] — 2026-04-17

### Added
- SmartEdge brand colors applied to egg shell — Royal Azure Blue `#0056B3` with Cyber Lime `#CCFF00` accents
- Lime XP pips with glow effect on the tamagotchi screen
- Brand-colored calendar heatmap (blue → lime gradient)
- SmartEdge-themed share card with navy background and lime accents
- Updated favicon to blue egg with lime dashed pattern

---

## [1.3.0] — 2026-04-17

### Added
- 8-bit sound effects generated via Web Audio API — no extra files needed
  - 🍖 Feed: happy ascending 4-note chirp
  - ★ Play: bouncy playful arpeggio
  - ⟳ Sync: quick two-tone blip
  - 🥚 Summon: egg hatch chime
  - ✨ Evolution: full 7-note fanfare with sparkle tones
- Sound on/off toggle on the setup screen

---

## [1.2.0] — 2026-04-17

### Added
- 🔥 Commit fire calendar — 14-week GitHub-style heatmap with fire heat colors
- Share card — downloadable PNG of your dragon's current stage
- Evolution animation — egg shell pulses with dramatic glow when levelling up
- Dragon spins and bounces during evolution with stage name flash on screen
- Dragon egg favicon embedded as SVG data URI — no extra file needed
- `og:image`, `og:title`, `og:description` meta tags for social sharing previews
- SmartEdge Marketing footer link back to SmartEdgeDM.com
- MIT License added to repo

---

## [1.1.0] — 2026-04-17

### Added
- Tamagotchi-style egg shell wrapping the entire UI
- Three working buttons: Feed 🍖, Sync ⟳, Play ★
- Screen messages appear inline on the tamagotchi display
- `commit.pet` branding on egg shell
- `index.html` renamed from `commit-dragon.html` for GitHub Pages compatibility
- Auto-loads username on page open
- `README.md` with screenshot, feature list, evolution table, and Buy Me a Coffee badge
- `.github/FUNDING.yml` — Buy Me a Coffee sponsor link

---

## [1.0.0] — 2026-04-17

### Initial Release
- Digital pet dragon that evolves based on GitHub public commit activity
- 5 evolution stages: 🥚 Egg → 🐣 Hatchling → 🦎 Wyrmling → 🐲 Drake → 🐉 Elder Dragon
- Live GitHub API integration — fetches last 100 public events, no login required
- Dragon vitals: streak, activity, and power bars
- Recent commit feed with repo names, messages, and timestamps
- Built with zero dependencies — pure HTML, CSS & JavaScript

---

Made with 💜 by [SmartEdge Marketing](https://SmartEdgeDM.com)
