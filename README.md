# Nura

Revenue-assurance infrastructure for German ambulatory care — turns every completed care visit into verified, auditable, billing-ready documentation.

## Structure

```
/               Marketing website (index.html)
/app            Caregiver app demo — interactive prototype (3 scenarios)
/assets         Logo mark and app-icon exports
```

## Running locally

Both `index.html` and `app/index.html` are self-contained static files — no build step, no dependencies. Open either directly in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000` for the website and `http://localhost:8000/app` for the app demo.

## GitHub Pages

Settings → Pages → Deploy from branch → `main` → `/ (root)`. The site and app will both be live at the resulting Pages URL (app at `/app/`).

## Notes

- Fonts (Satoshi) load from Fontshare's CDN at runtime — an internet connection is required for correct typography.
- The app demo simulates the product flow client-side; it is not connected to a real backend.
