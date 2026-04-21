# Slide Deck — 21 slides

The authoritative slide deck is `index.html`. This document is a quick-reference index only — for visual truth and speaker notes, open the HTML and press `S` (or read `speaker-notes.md`).

## Aesthetic (shared across deck)

- Background: pure black (#000)
- Accent: neon purple `#C278FF` / magenta `#FF3EE1`
- Secondary: cyan-blue `#4BA3FF`
- Font: monospace stack (IBM Plex Mono → JetBrains Mono → Menlo → Consolas → ui-monospace)
- Frame: thin purple outlined border
- Imagery: full-bleed where possible, `object-fit: cover`
- Chapter-break slides (LIVE DEMO, YOUR TURN) have CSS RGB-split glitch animation every ~3 sec

## 21-slide index

| # | Slide | Purpose |
|---|-------|---------|
| 1 | Title (with dimmed vaporwave bg) | Cold open — title + tagline |
| 2 | Two tracks | Artist / Coder split reveal |
| 3 | 2012 · the camera | Photography origin story, hero photo as dimmed bg |
| 4 | Brno walks · colour & bloom | 2×2 grid of spring/saturated photos |
| 5 | Brno walks · city & mood | 2×2 grid of urban/nocturnal photos |
| 6 | Brno walks · close & quiet | 2×2 grid of intimate/autumn photos |
| 7 | 2016 glitch-user era | 2×2 grid: Tlenogram, D3lta, SLMMSK, 8Bit Photo Lab |
| 8 | Track B · day-job coder | Text block (CS 2017, Python, MIDI 2019) |
| 9 | ComputerArt2018 · dormant seed | 2×2 grid of math-function image generator renders |
| 10 | THE RETURN · 2024 | Text block — "78 weeks ago..." + apps used |
| 11 | FACES (2024–25) | 2×2 grid of renaissance face pieces |
| 12 | NOT-FACES (2024–25) | 2×2 grid of text/sculpture/abstract pieces |
| 13 | The spark (2025) | Full-bleed PyCharm render + caption |
| 14 | Glitch Please! reveal | App icon + wordmark + feature list |
| 15 | LIVE DEMO | Chapter break (one word) + demo flow preview |
| 16 | Hold (demo buffer) | Identical to slide 15, used if phone mirror drops |
| 17 | Code moment — ORIGINAL algorithm | Live HTML-rendered Kotlin + plain-English explainer |
| 18 | YOUR TURN | Chapter break + challenge teaser |
| 19 | Challenge | Default sculpture + rules + QR + prize split |
| 20 | Thanks | Credits + renaissance supporters list |
| 21 | Q&A | Final glitch + handle + Play Store + hashtag |

## Timing

Total: 30 min. Story (0:00–14:00) · Live demo (14:00–27:00) · Close (27:00–30:00). See `speaker-notes.md` timing map for per-segment breakdown.

## Live code demo (slide 17)

The code block is rendered as live syntax-highlighted HTML — no external screenshot required. Algorithm shown: **ORIGINAL** (simplified from `app/src/main/java/com/michaljenco/glitchplease/GlitchEngine.kt:577-591`). Highlights the `mod256` wrap lines, where byte-overflow produces the glitch artifact.

## Missing assets (see `images/README.md`)

- App icon for slide 14
- Default sculpture + Play Store QR for slide 19
- Final signature piece for slide 21
