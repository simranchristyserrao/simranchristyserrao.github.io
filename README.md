# Simran Christy Serrao — Academic Portfolio

Static personal website (plain HTML + CSS, no build step) hosted on GitHub Pages.

## Files
- `index.html` — page content
- `style.css` — theme (Chocolate Kiss `#5c3a21` / Off-White `#fdfbf7`)
- `.nojekyll` — tells GitHub Pages to serve files as-is (skip Jekyll processing)

## Preview locally
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish / update
```bash
git add .
git commit -m "Update site"
git push origin main
```
GitHub Pages: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
