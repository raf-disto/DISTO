# DISTO — disto.ag

Static site, no build step.

## Files
- `index.html` — main page
- `image-slot.js` — drag-and-drop image placeholder component
- `assets/` — logos + sound files

## Deploy
Push everything in this folder to your repo root, then connect the repo to Cloudflare Pages (or Netlify / Vercel).
- Build command: *empty*
- Output directory: `/`

## Local preview
Open `index.html` in a browser. Note that some browsers require serving over HTTP for the audio fetch to work — use `python3 -m http.server` from this folder if needed.
