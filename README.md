# CPD Bethel U11 — Interactive Training

Welsh-language interactive football training presentation for CPD Bethel U11.

## Files
- `index.html` — Main presentation; runs at `/`.
- `coach.html` — Separate coaching notes; runs at `/coach.html`.

Both files are self-contained and work offline. No build process, packages or database required.

## Cloudflare Pages
1. Connect GitHub repository `Clic-Cymru/bethel-training` to Cloudflare Pages.
2. Use production branch `main`, no framework preset, root directory `/`.
3. Use no build command (if the UI requires one, `exit 0`).
4. Set build output directory to `.`.

## Local use
Open `index.html` in a browser and `coach.html` on another device if shared or hosted.

## Important
The repository and Cloudflare Pages deployment may be public. Do not add private player details. The coaching notes at `/coach.html` are not access-controlled.