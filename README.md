# Sri Venkateshwara Jeweller — website

Static site for GitHub Pages.

## Publish
1. Create a new public repo on GitHub (e.g. `svj-website`).
2. Upload **everything in this folder** to the repo root — including the hidden file `.nojekyll`. Collection photos are in `assets/collections/`.
   - Web upload hides dotfiles on some systems; if so, use GitHub Desktop or:
     ```
     git init && git add -A && git commit -m "Site"
     git branch -M main
     git remote add origin https://github.com/<you>/svj-website.git
     git push -u origin main
     ```
3. Repo → Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
4. Site goes live at `https://<you>.github.io/svj-website/` in about a minute.

## Updating daily rates
Edit `index.html`, search for `rate22`, `rate24`, `rateSilver` and change the default numbers, then commit.
