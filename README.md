# Pallavi Phadtare — portfolio site

Static site, no build step. Files: `index.html`, `cv.pdf`, `.nojekyll`.

## Deploy on GitHub Pages
1. On GitHub, create a public repo named exactly `<your-username>.github.io`.
2. Upload `index.html`, `cv.pdf` and `.nojekyll` to the root of the `main` branch
   (Add file → Upload files → Commit). `.nojekyll` is a hidden file; drag it in or skip it, the site works without it.
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)` → Save.
4. After a minute or two the site is live at `https://<your-username>.github.io`.

To update later, edit `index.html` (or replace `cv.pdf`) and commit.
