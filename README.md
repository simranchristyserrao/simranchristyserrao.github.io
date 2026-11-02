# Simran Christy Serrao — Academic Website

Static personal website (plain HTML + CSS, no build step) hosted on GitHub Pages.

## Files
- `index.html` — main homepage
- `blog.html` — blog essay & artwork
- `style.css` — theme (Earth Brown `#3d2b1f` / `#a45a32` / Sand `#f7f4ee`)
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
