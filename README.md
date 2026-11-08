# Sana — Locked Video Bridge Page

Mobile-first 9:16 dark "Locked Video Player" landing page for Sana's social profile.

- Blurred background image inside the player frame (`filter: blur(8px)`)
- 🔴 LIVE • Exclusive Private Clip (03:42) badge + pulsing play button
- "18+ Only • Click Play to Continue" warning
- The whole player (and Play button) redirects immediately to the monetized link:
  `https://urlbit.pro/MbVaf`

## Files

- `index.html` — the whole page, standalone. No build step, no backend.
- `vercel.json` — static-site config for Vercel.

## Deploy

- GitHub Pages: repo Settings → Pages → Deploy from branch `main`, folder `/ (root)` →
  `https://saifgamarz.github.io/sana-bridge/`
- Vercel: import this repo as a static site (no framework, no build command) →
  `https://sana-bridge.vercel.app` (name may vary if taken)

## Swap the photo

Replace the two Unsplash URLs in `index.html` (background + avatar) with Sana's own
photo URL. The background stays blurred via CSS; the avatar shows it sharp.
