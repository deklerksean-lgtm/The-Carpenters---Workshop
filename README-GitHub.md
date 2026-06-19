# CabinetWizard — Web App

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload all files from this folder
3. Go to Settings → Pages → Source → Deploy from branch → main / (root)
4. Your app will be live at: https://yourusername.github.io/your-repo-name/

## Files
- `index.html` — Main application (self-contained, includes all JS/CSS)
- `manifest.json` — PWA manifest (install to home screen)
- `sw.js` — Service worker (offline support)
- `icon-*.png` — App icons
- `.github-static.yml` — Rename to `.github/workflows/static.yml` for auto-deploy

## PWA Install
Users can click "Install App" in the browser address bar to install
CabinetWizard as a Progressive Web App on their device.
