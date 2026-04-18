# Changelog

All notable changes to Commit Dragon are documented here.

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
  - Royal blue egg with glowing screen, shine highlights, and bobbing animation
  - Lime accent stripe around egg equator
  - Three working buttons: Feed 🍖, Sync ⟳, Play ★
- Screen messages appear inline on the tamagotchi display
- Feed button triggers bounce animation with happy messages
- Play button triggers spin animation
- Sync button fetches live GitHub data and triggers evolution animation if levelled up
- Dragon stage label and XP pip dots on screen
- `commit.pet` branding on egg shell
- `index.html` renamed from `commit-dragon.html` for GitHub Pages compatibility
- Auto-loads username on page open
- `README.md` with screenshot, feature list, evolution table, and Buy Me a Coffee badge
- `.github/FUNDING.yml` — Buy Me a Coffee sponsor link (`buymeacoffee.com/smartedge`)

---

## [1.0.0] — 2026-04-17

### Initial Release
- Digital pet dragon that evolves based on GitHub public commit activity
- 5 evolution stages: 🥚 Egg → 🐣 Hatchling → 🦎 Wyrmling → 🐲 Drake → 🐉 Elder Dragon
- Live GitHub API integration — fetches last 100 public events, no login required
- Dragon vitals: streak, activity, and power bars
- Recent commit feed with repo names, messages, and timestamps
- Speech bubbles with stage-appropriate dragon personality
- XP progress bar toward next evolution
- Stats panel: total commits, day streak, repo count
- Evolution track showing all 5 stages
- Back button to change GitHub username
- Built with zero dependencies — pure HTML, CSS & JavaScript

---

Made with 💜 by [SmartEdge Marketing](https://SmartEdgeDM.com)
