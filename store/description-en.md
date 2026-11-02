# Color Flood — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io, ≤200 chars)

Flood the board with one color! Pick a color each turn to spread from the
top-left tile. Clear 14×14 in 25 moves, chain wins to grow the grid to 18×18.

## Details

- Genre: Puzzle / Casual / Strategy
- Controls: Mouse / Touch (tap a color dot). Keyboard: 1–6 to pick a color,
  H to toggle hint badges, Enter/Space for menus.
- Features: 6-color accessible palette (distinct hues + lightness),
  real-time capture-count hint badges (toggleable), 3-star win rating,
  win-streak progression (14×14 → 16×16 → 18×18 with tighter step budgets),
  streak & best-save records, progress bar, procedural graphics & sounds,
  single-file HTML5 (no external assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
flood-it, puzzle, casual, colors, logic, brain, single-file, hexirp

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] loadingStart / loadingStop / gameplayStart / gameplayStop / happytime events wired
- [x] Responsive (canvas auto-resizes, portrait & desktop friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 (1280×720) — to capture from live game
- [ ] Screenshot raw — to capture from live game

## GameDistribution
- Upload color-flood-gd.zip (contains only index.html)
- The GameDistribution SDK v2 script auto-loads on gamedistribution / gd.games
  domains; nothing else to configure.

## itch.io
- Upload zip (color-flood-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 420×760, kind: html
- Pricing: $0 (donations optional)
