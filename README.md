# tigerc12.github.io

Personal portfolio site for Youshi (Tiger) Chen. Plain HTML + CSS, no build step.

## Files

- `index.html` — the whole site (edit text here)
- `style.css` — styling (light + dark, responsive)
- `resume/` — the resume PDF linked from the site
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Preview locally

```bash
python -m http.server 8765
```

Then open http://localhost:8765.

## Deploy to GitHub Pages (free, ~2 minutes)

1. Create a **public** repo on GitHub named exactly `TigerC12.github.io`.
2. From this folder:

   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/TigerC12/TigerC12.github.io.git
   git push -u origin main
   ```

3. On GitHub: repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at https://tigerc12.github.io within a minute or two.

## Updating resumes

Drop the new PDF into `resume/` with the same filename and push. Links do not change.
