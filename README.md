# Empire Rising — Offline Idle Business Tycoon

An original, mobile-friendly idle business game with **zero dependencies**, **no ads**, and **no backend**.

## Play locally

Open `index.html` in a browser. Gameplay and local saves work without a server. To test installability and the offline service worker, serve the directory on localhost:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Visit once while online so the service worker can cache the files.

## Publish on GitHub Pages

1. Create a new public GitHub repository.
2. Upload **all files in this folder** to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Open the Pages URL shown by GitHub after deployment.

## Features

- 9 businesses with compounding upgrades and hiring managers
- 5 empire-wide technology upgrades and 4 districts
- Tap-to-work starter earnings
- Passive earnings, even when you close the game (75% rate, capped at 8 hours)
- Prestige progression with permanent income multipliers
- Local autosave, JSON export/import, and reset
- Installable PWA with offline cache on HTTPS or localhost
- Responsive desktop and mobile design

## Save behavior

Saves use browser `localStorage` and stay on that browser/device. Use **Export Save** and **Import Save** to transfer progress. Clearing site data deletes local saves unless exported. Browser private mode may not retain saves.

## License

MIT — see LICENSE.
