# TaskNama-CSE326

A single-page web app (`index.html`) – plain HTML, CSS and JavaScript. The background video is embedded inside the file, so no build step or extra assets are needed.

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository (branch `main`).
2. In the repo go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
3. The included workflow (`.github/workflows/pages.yml`) deploys automatically on every push.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

(Alternative without Actions: Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.)

## Files

- `index.html` – the app (unchanged)
- `assets/` – original background video files (not referenced by the page; kept for reference)
- `.nojekyll` – tells GitHub Pages to serve files as-is
