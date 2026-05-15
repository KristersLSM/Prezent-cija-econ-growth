# Temperature Shocks & Economic Growth — Referee Presentation

Interactive presentation on Dell, Jones & Olken (2012), *Temperature Shocks and Economic Growth: Evidence from the Last Half Century*, AEJ Macro 4(3).

By **Amelie Hucko** and **Kristers Grobins** — Group 7.

## Hosting on GitHub Pages

1. Create a new public repository on GitHub (e.g. `djo-presentation`).
2. Upload `index.html` (and this `README.md`) to the repo root.
3. Go to **Settings → Pages**.
4. Under **Source**, pick **Deploy from a branch** → `main` → `/ (root)` → **Save**.
5. Wait ~30 seconds. Your slides will be live at `https://<your-username>.github.io/djo-presentation/`.

The site loads straight into slide 1 — no landing page, no PDF.

## Navigation

| Action | How |
|---|---|
| Next slide | `→` · `Space` · `PageDown` · swipe left · click right edge · `Next` button |
| Previous slide | `←` · `PageUp` · swipe right · click left edge · `Prev` button |
| Jump to slide 1–9 | Number keys `1`–`9` (`0` jumps to slide 10) |
| First / last | `Home` / `End` |
| Direct link to slide *n* | Add `#n` to the URL (e.g. `…/index.html#7`) |

The slide indicator sits in the bottom-right corner (e.g. `07 / 18`). A progress bar runs along the very top of the screen.

## Slide outline (18 slides, ~15–18 min for two presenters)

| # | Slide | Suggested speaker |
|---|---|---|
| 1 | Title | both |
| 2 | The puzzle: hot countries are poor | A |
| 3 | Two old approaches | A |
| 4 | DJO's strategy | A |
| 5 | Level vs growth effects | A |
| 6 | Specification | K |
| 7 | Headline result (Table 2) | K |
| 8 | Lag dynamics (Table 3) | K |
| 9 | Channels: ag · industry · politics | K |
| 10 | Robustness (Table 4) | K |
| 11 | Medium-run (Section IV) | A |
| 12 | Implications for IAMs | A |
| 13 | Critique 1: poor-rich bundling | A |
| 14 | Critique 2: level vs growth fragility | K |
| 15 | Critique 3: politics as consequence | K |
| 16 | Verdict | both |
| 17 | One thing to remember | both |
| 18 | Thank you / Q&A | both |

Speaker assignments are a suggestion — feel free to redistribute.

## Tech notes

- Single HTML file, no build step, no dependencies beyond two Google Fonts (Fraunces + Inter Tight + JetBrains Mono).
- Works offline if you self-host the fonts.
- Tested in Chrome, Firefox, Safari, mobile Safari, mobile Chrome.
- All styling and motion is pure CSS; the JS handles only navigation.
