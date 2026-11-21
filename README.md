# Project 85 – Version 2

Updated warm-neutral and blush-pink visual theme, minimalist P85 app icon, matching settings cog, and refreshed offline cache. Existing app data continues to use the same local storage key (`project85`).

A lightweight, installable personal fitness and nutrition tracker.

## Included
- Workout schedule and completion logging
- Food diary with calories and protein
- Daily steps
- Weight, waist and hip check-ins
- Local browser storage
- JSON backup, import and progress export
- Basic offline caching after first load

## Publish it for iPhone
The app needs to be hosted on an HTTPS website before iOS can add it to the Home Screen as an app.

One straightforward free option is GitHub Pages:
1. Create a new GitHub repository.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
4. Wait for GitHub Pages to provide the HTTPS site address.
5. Open that address in Safari on your iPhone.
6. Tap Share → Add to Home Screen → Add.

## Data and privacy
Entries are stored in localStorage in the browser on the device. They are not automatically synced to ChatGPT or another device. Use Settings → Export full backup regularly. Export progress summary to share your records for a plan review.

This is a starter tracker, not a medical device. Calorie and nutrition values are estimates and should be adjusted to individual needs.
