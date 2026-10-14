# SIEGE 2026: SCAD Game Development and Creative Technology

Presentation deck for SCAD at SIEGE 2026. Plain HTML, no build step.

## Run it

- **Online:** open the GitHub Pages link for this repo. Works on a laptop or a phone.
- **Offline:** download `SIEGE-2026-SCAD-offline.html` and open it in Chrome or Edge. Every image and font is built into that one file, so it needs no internet.

## Controls

| Action | Keyboard | Phone or tablet |
|---|---|---|
| Next / previous slide | Arrow keys, Space, Page Up/Down | Swipe left / right, or tap the right / left side |
| Style chooser (SCAD, Studio 2026, Halloween) | S | Swipe up |
| Presenter view (current and next slide, timer, speaker notes) | P | Laptop only |
| Notes over the slide | N | |
| Fullscreen | F | |
| Jump to a slide | add `#5` to the address | same |
| Force a style | add `?style=halloween` or `?style=studio` to the address | same |

## Speaker notes

Open presenter view with P and type in the speaker notes box. Notes save in that browser automatically. Use **Save deck with notes** to download a copy of the deck with your notes written into the file, then replace `index.html` (or the offline file) with it and commit.

## Files

- `index.html` is the deck. Each `<section class="slide">` is one slide; `data-hidden` slides are skipped.
- `img/` and `fonts/` are used by `index.html`.
- `SIEGE-2026-SCAD-offline.html` is the same deck as a single self-contained file. Rebuild it after editing `index.html`.
