# Flutter in the Age of AI

Talk deck and research notes for **Flutter in the Age of AI — From Developer to Product Thinker**.

## Contents

- `flutter-in-the-age-of-ai-en.html` — slide deck (English)
- `flutter-in-the-age-of-ai-research.md` — research notes
- `assets/` — images and media used in the deck

Part of [luthfiarifin/research](https://github.com/luthfiarifin/research) (linked as a submodule).

## Viewing the deck

It's a single, dependency-free HTML file — just open `flutter-in-the-age-of-ai-en.html` in any browser.

- **Navigate:** `→` / `←` / `Space` / `PageUp`–`PageDown`, mouse wheel, or swipe. `Home` / `End` jump to first/last slide.
- **Edit inline:** press `E` (or hover the top-left corner) to make any text editable; edits auto-save to `localStorage`. `Ctrl/Cmd+S` exports a fresh copy of the HTML.
- The stage is authored at a fixed **1920×1080** and scaled to fit the viewport, so it looks identical on any screen and prints cleanly to PDF (one slide per page).

## How I built this deck

The deck was generated with [**frontend-slides**](https://github.com/zarazhangrui/frontend-slides) — a Claude Code skill that builds beautiful, zero-dependency HTML presentations from a content outline (no design expertise needed).

Install the skill in Claude Code:

```
/plugin marketplace add https://github.com/zarazhangrui/frontend-slides
/plugin install frontend-slides@frontend-slides
```

Then invoke it with `/frontend-slides:frontend-slides`. My workflow:

1. **Research first** — I drafted the talk's argument and sources in `flutter-in-the-age-of-ai-research.md`, then turned that into a slide-by-slide outline.
2. **Generate** — fed the outline to the skill and picked a visual direction from its style previews.
3. **Style** — committed to **Neo-Grid Bold** (see below) and let the skill produce the full single-file HTML.
4. **Drop in real assets** — replaced placeholders with real screenshots from my own workflow in `assets/`.
5. **Iterate** — tuned copy directly in the browser via the built-in inline edit mode (`E`), exported, and committed.

## Style: Neo-Grid Bold

A high-contrast editorial system — ecru paper, ink black, and a single neon-lemon signal color. Depth comes purely from color adjacency: no shadows, no rounded corners. All tokens live in `:root` at the top of the HTML, so retuning the whole deck is a one-place edit.

| Token | Value | Role |
|---|---|---|
| `--paper` | `#F5F4EF` | default panel fill |
| `--bg` | `#ECECE8` | frame behind the 40px inset |
| `--ink` | `#0A0A0A` | structural black — text, dividers, inverted panels |
| `--accent` | `#E6FF3D` | neon lemon — the only chromatic signal |
| `--muted` | `#8A8A85` | reserved graphite |

- **Type:** Space Grotesk (700 uppercase display + 400 body) paired with JetBrains Mono for uppercase labels.
- **Layout:** every slide composes inside one universal **12-column × 8-row grid** (40px inset, 12px gap).
- **Panels:** four kinds — `paper` (default), `ink` (inverted), `lemon` (signal), and `photo` (full-bleed screenshots).
- **Emphasis:** `<mark>` paints a lemon swatch; `<em>` switches text to lemon (no italics).
