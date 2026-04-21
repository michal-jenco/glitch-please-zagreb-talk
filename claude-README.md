# Glitch Festival 2026 — Talk materials

Friday **24 April 2026**, 19:30–20:00 · Infoshop Pippilotta, Zagreb
International Glitch Festival · Glitch Cult strand

## Files

- **[presentation.html](index.html)** — the actual talk deck. Self-contained HTML, no internet required, works in Chrome on Android tablet. 15 slides. Drop it on your tablet and open. See [images/README.md](images/README.md) for how to add the imagery.
- **[speaker-notes.md](speaker-notes.md)** — what you'll have in front of you on stage. Timing map, segment-by-segment notes, demo blocking, failure fallbacks. The HTML deck also embeds these notes — press `S` during the presentation to toggle a presenter overlay.
- **[slides.md](slides.md)** — slide-by-slide spec that the HTML was built from. Keep as reference / single source of truth when editing.
- **[challenge-card.md](challenge-card.md)** — the take-home challenge rules, paste-ready IG post, and open decisions (payment method).
- **[images/](images/)** — drop-zone for slide imagery. See [images/README.md](images/README.md) for the expected filenames.

## Presenting from your Android tablet

1. Copy this whole folder (HTML + images/) onto your tablet (USB, cloud, Syncthing, whatever).
2. Open `presentation.html` in **Chrome**.
3. Tap the fullscreen button in Chrome's menu (or press F if you have a keyboard).
4. **Tap the right two-thirds** of the screen to advance, **left third** to go back. Swipe works too.
5. To see your notes: press `S` (with a keyboard) or navigate with one finger while checking printed notes. For a full presenter view you'd need a second screen.
6. **Backup:** print `presentation.html` to PDF from Chrome as a fallback. The CSS has a print media query that flattens the deck to one slide per page.

### Keyboard shortcuts (if you use a BT keyboard / clicker)
| Key | Action |
|---|---|
| → / Space / PageDown | Next slide |
| ← / PageUp | Previous slide |
| S | Toggle presenter notes |
| F | Toggle fullscreen |
| B | Black out screen |
| Home / End | Jump to first / last slide |
| 1–9 | Jump to slide N |
| ? or H | Help overlay |
| Esc | Close any overlay |

## Outstanding items

All major narrative/structural decisions are locked. What's left is asset gathering:

- [ ] MIDI sequencer screenshot (slide 5) — if not found by slide-build day, use a clean dark PyCharm window as fallback
- [ ] Glitch Please! app icon, high-res (slide 8)
- [ ] Play Store QR (slide 13) — generate once listing is public
- [ ] Syntax-highlighted screenshot of `ColorGateGlitch.kt:36-63` (slide 11)
- [ ] Final portrait/signature glitch piece for slide 15 (Q&A)
- [ ] Payment method ready for winners (Revolut / PayPal / IBAN)

**Locked challenge details** (for slide 13 / IG post):
- Deadline: **Sun 26 Apr 2026, 23:59 CET**
- Winners announced: **Mon 27 Apr 2026**
- Prize split: **€30 / €20 / €10**

## Rehearsal plan

1. **First read-through** (no slides) — read `speaker-notes.md` aloud with a timer. Target 28–29 min.
2. **Build the deck** using `slides.md` once the outstanding images are gathered.
3. **Second rehearsal** — full run with slides + phone mirror. Cut whatever drags.
4. **Dress rehearsal** — night before, in a space with a projector if possible.

## Narrative arc (locked)

Two tracks — **artist (2016 →)** and **coder (2017 →)** — ran in parallel rooms. **No friction, no frustration** ever pushed them together.

But one hobby project in 2018, **ComputerArt2018**, sat quietly in the middle: a math-function image generator Michal built, saved, showed nobody, and forgot about for seven years.

In 2025, on impulse — "what if I coded my own glitch algorithm?" — he opened PyCharm and discovered the math he reached for was the same math from 2018. The door between the rooms had been open all along; he just hadn't walked through it. First result was something no existing app produced. That PyCharm moment became **Glitch Please!**
