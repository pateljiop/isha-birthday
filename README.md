# Isha ke naam — A Little Birthday World

A mobile-first, Hinglish birthday surprise made for Isha. The site is a static HTML/CSS/JavaScript experience and is designed to work on phones as well as desktop screens.

## What's inside

- A personal welcome screen and birthday wishes.
- Small interactive wish cards, flower messages, and a comfort corner.
- A nursing-study encouragement section.
- A short friendship mini-quest with an optional WhatsApp response. The visitor reviews the pre-filled message and sends it manually; nothing is sent automatically.
- An interactive Three.js birthday scene:
  1. Light the cake candles together.
  2. Blow the candles out together.
  3. Cut the birthday cake.
  4. Hariom feeds Isha a bite of cake.
  5. Isha feeds Hariom a bite of cake.
  6. Pop the balloons and finish the celebration.
- A final birthday wish and replayable celebration.

## Run locally

Because the site is static, no build step or backend is required.

1. Clone the repository.
2. Open `index.html` in a browser, or serve the folder with any static file server.
3. Keep an internet connection available for the Three.js module loaded from jsDelivr.

## GitHub Pages deployment

The workflow in `.github/workflows/pages.yml` deploys the repository root to GitHub Pages whenever a commit is pushed to `main`.

Site URL: https://pateljiop.github.io/isha-birthday/

If Pages is not enabled yet, open **Settings → Pages**, select **GitHub Actions** as the build and deployment source, and save.

## Add personal photos later

The birthday scene currently uses illustrated placeholder avatars. When the photos are ready and approved for use:

1. Add an `assets/` folder.
2. Add only the selected photos that Isha is comfortable sharing on this page.
3. Replace the relevant illustrated placeholders with optimized images and meaningful alt text.
4. Check the result on a phone before merging.

Do not commit private photos, screenshots, or personal recordings without permission.

## Technical notes

- Static HTML, CSS, and JavaScript; no backend or database.
- Three.js is loaded from a CDN for the interactive 3D scene.
- The page includes keyboard focus styles, semantic sections, live status text, responsive layouts, and reduced-motion CSS support.
- No analytics or tracking code is included.
- WhatsApp opens a pre-filled draft only after a visitor chooses a response; the visitor must send it manually.
