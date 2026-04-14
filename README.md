# Portfolio (GitHub Pages)

Static portfolio served as the site root (`index.html`).

GitHub profile: [github.com/LanaKhalifa](https://github.com/LanaKhalifa)

## Publish

1. Create a new **empty** repository on GitHub named e.g. `portfolio` (no README from the web UI).
2. In this folder:

```bash
cd "/Users/lanakhalifa/Desktop/find_phd 2/portfolio-github"
git init
git add .
git commit -m "Add portfolio for GitHub Pages"
git branch -M main
git remote add origin https://github.com/LanaKhalifa/portfolio.git
git push -u origin main
```

If you chose a different repo name, change the last path segment in `remote` and in the site URL below.

3. On GitHub: open the repo → **Settings → Pages → Build and deployment → Branch**: `main`, folder **`/ (root)`**, Save.

The site will be at **https://lanakhalifa.github.io/portfolio/** if the repo is `portfolio` (GitHub uses your username in **lowercase** in the hostname).

After enabling Pages, confirm the exact URL in the green notice on **Settings → Pages**.

## Contents

- `index.html` — full portfolio (figures embedded as data URLs where applicable).
- PNG files referenced by relative paths from the HTML.
