# PHOTOFLIY — Aditya Bhagat Portfolio

Recreation of https://sites.google.com/view/photofliy/home, rebuilt as a fast,
cinematic single-page site with animations (Ken Burns hero, staggered headline
reveal, marquee, scroll reveals, filter animations, lightbox).

## Files

- `index.html` — the portfolio site (loads `portfolio.json`, falls back to embedded data)
- `portfolio.json` — all editable content (site settings + works)
- `admin.html` — separate, unlinked admin page: edit content, download a new
  `portfolio.json`, replace it in this repo. Site updates in 1–2 minutes.
- Photos are hotlinked from the original Google Site (Google blocks automated
  downloads, so no local copies). They load normally for real visitors. If
  Aditya later sends the original files, drop them in `assets/` and point
  `portfolio.json` at them. The original site has no model photo, so the
  Model card is a typographic tile by design — no mismatched photo used.

## Update flow (phone-friendly)

1. Open `admin.html` → edit → Download `portfolio.json`.
2. GitHub app/browser → repo → `portfolio.json` → Edit → paste → Commit.
3. GitHub Pages rebuilds automatically.

Instagram link and location are intentionally left blank in `portfolio.json`
(the original site does not publish them) — fill them in via Admin when known.
