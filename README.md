# Growthstrom website

The site lives in `site/`: one `index.html` plus `assets/`. No build step.

- Preview: run `python3 -m http.server` inside `site/` and open http://localhost:8000
- Deploy: zip the contents of `site/` (index.html and assets/ at the top level) and upload to any static host.

## Swapping in new visuals
- Replace `site/assets/hero.jpg`, `step-1.jpg`, `step-2.jpg`, `step-3.jpg` with images of the same names (16:9, about 1920px wide).
- To add the scroll-driven hero video later, add `site/assets/hero-scrub.mp4` and set `VIDEO_URL` near the top of the script in `index.html`.

## Before launch
- The audit form currently shows a thank-you message only. Connect it to an inbox or a form service.
- Patch `og:image` and `og:url` at the `DEPLOY STEP` comment with the live address.
