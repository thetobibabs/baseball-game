[README.md](https://github.com/user-attachments/files/28816357/README.md)
# Backyard Baseball Duel, iPhone PWA Edition

This is an installable mobile web app version of the baseball game.

## What is included

- iPhone-friendly full-screen layout
- Touch controls
- Offline support through a service worker
- PWA manifest
- iPhone home screen icon
- Difficulty settings
- 3, 6, or 9 inning games
- Saved settings
- Sound toggle
- Balls, strikes, walks, strikeouts
- Singles, doubles, triples, home runs
- Errors and double plays
- CPU opponent

## How to use on iPhone

iPhone does not install local ZIP files as apps directly. You need to host the folder online first.

Recommended free options:

1. Netlify Drop
   - Go to Netlify Drop in a browser.
   - Drag the entire `backyard_baseball_pwa` folder onto the page.
   - Open the generated URL on your iPhone using Safari.
   - Tap Share.
   - Tap Add to Home Screen.

2. GitHub Pages
   - Upload these files into a GitHub repo.
   - Enable Pages.
   - Open the GitHub Pages URL in Safari.
   - Tap Share, then Add to Home Screen.

3. Vercel
   - Upload as a static project.
   - Open the deployed URL in Safari.
   - Tap Share, then Add to Home Screen.

After the first load, the game is cached and should work offline from the Home Screen.

## Important iPhone note

The app must be served from a website for service worker offline mode to work. Opening `index.html` directly from the Files app is not enough on iPhone.
