# AKSB Global — website v2 (preview)

Rebuild of the AKSB Global site on the motion grammar of fluid.glass (Exo Ape), rebranded
blue-first for AKSB. Live preview: https://shazwan-mysense.github.io/aksb-v2/ — the current
production site stays at https://zebwan.github.io/aksb-global/.

- `index.html` — the whole page; scope detail panels are `<template>`s at the bottom.
- `css/site.css` — fluid rem system (1rem = 10px at 1600 wide), every component; values match
  `TEMPLATE-TEARDOWN.md`.
- `js/site.js` — GSAP 3.13 + ScrollTrigger + SplitText + DrawSVG, Lenis 1.3; intro, pill header,
  menu, cursor, line reveals, pinned banner, sliders, side panels, mailto enquiry form.
- `vendor/` — the libraries, vendored (no build step, no Node).
- `images/` — same photo and logo set as the production repo.

Deploys on push to `main` via GitHub Actions (static upload, no build).
