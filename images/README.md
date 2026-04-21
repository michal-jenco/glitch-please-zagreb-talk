# Presentation images

The deck is now 21 slides. Images are organized across this folder + 4 subfolders (`photos/`, `D3lta/`, `8bitphotolab/`, `glitches-from-2024/`). Most images are already wired into `index.html` using their original filenames — no renaming required.

## What's wired and where

| Slide | Image(s) | Location |
|-------|----------|----------|
| 1 — Title | `vaporwave.gif` (dimmed bg) | `images/` |
| 3 — 2012 · the camera | golden-hour harbor (dimmed bg) | `photos/565708447_..._n.jpg` |
| 4 — Brno walks · colour & bloom | 4 pink/blossom photos | `photos/492057170`, `492463517`, `492373490`, `492395772` |
| 5 — Brno walks · city & mood | 4 urban/nocturnal photos | `photos/573063697`, `568345519`, `568427188`, `573584370` |
| 6 — Brno walks · close & quiet | 4 intimate/autumn photos | `photos/492196927`, `492401899`, `568260419`, `561349757` |
| 7 — 2016 glitch-user grid | Tlenogram + D3lta + SLMMSK + 8Bit Photo Lab | `tlenogram.jpg`, `D3lta/482343514...`, `slmmsk.jpg`, `8bitphotolab/486951188...` |
| 9 — ComputerArt2018 | 4 math-art renders | `47577122...`, `47423402...`, `47684833...`, `47436207...` |
| 11 — FACES (2024–25) | 4 renaissance face pieces | `glitches-from-2024/Screenshot 2026-04-21 at 21.37.52.png`, `21.38.07`, `21.39.50`, `21.40.09` |
| 12 — NOT-FACES (2024–25) | 4 renaissance non-face pieces | `glitches-from-2024/Screenshot 2026-04-21 at 21.34.42.png`, `21.35.31`, `21.35.12`, `21.37.22` |
| 13 — The spark (2025) | Tessellation / spiral staircase | `1739923913-6 (1).png` |
| 19 — Challenge | Default sculpture (source image) | `default-sculpture.jpg` — **MISSING** |

## Still to produce / gather

| Filename | Slide | What it is |
|----------|-------|------------|
| `glitch-please-icon.png` | 14 (Glitch Please! reveal) | App icon, square, high-res (export from mipmap or Play Store) |
| `default-sculpture.jpg` | 19 (Challenge) | Clean classical sculpture bust (the default startup image) |
| `playstore-qr.png` | 19 (Challenge) | QR code → Play Store listing (any QR generator) |
| `final-piece.jpg` | 21 (Q&A) | One signature glitch of your choice |

## Swap-in candidates (already on disk, unused)

- `D3lta/` — 3 other D3lta pieces you didn't pick for slide 7
- `8bitphotolab/` — 3 other 8Bit pieces you didn't pick for slide 7
- `photos/` — 10 other photos not used in the 3 grid slides (e.g., `492375003`, `492384801`, `492401899`, `492410461`, `492475650`, `492536777`, `492363228`, `565708447` — used as bg but also good grid candidate, `573333676`, `574299871`, `568505146`)
- `glitches-from-2024/` — 15 other renaissance screenshots not in the FACES/NOT-FACES grids
- `2025-sculpture-glitch.jpg` — the purple/blue glitched bust (optional swap for slide 13)

To swap any pick: edit the relevant `<img src="images/...">` and matching `data-name="..."` in `index.html`. No file renaming needed.

## Subfolders

- **`photos/`** — 22 photographs from Michal's 2012–2016 photography practice in Brno
- **`D3lta/`** — 4 D3lta glitch-app pieces from 2016
- **`8bitphotolab/`** — 4 8Bit Photo Lab pieces from 2016
- **`glitches-from-2024/`** — 23 Instagram screenshots from the 2024–25 renaissance era (mix of artwork + IG post screenshots)

## Verifying

Open `index.html` in Chrome. Striped magenta placeholders with `⚠ IMAGE: filename` text = image not loading (wrong path or not saved yet). Real image rendering = correctly wired.

## Aspect ratio notes

CSS uses `object-fit: cover` throughout. Portrait, landscape, and square images all work — the grid cells and full-bleed slides centre-crop to fit. Keep files under ~1 MB each for snappy tablet performance (`vaporwave.gif` is the one exception at ~11 MB).
