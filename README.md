GitHub Pages quick setup for wdd130
=================================

Follow these steps to get your GitHub Pages site serving the `index.html` in this repository.

Checklist
- [ ] Repository name is `wdd130` (lowercase) under your GitHub account `israelessien48-art`.
- [ ] `index.html` is located at the repository root (this repo already contains it).
- [ ] Push changes to the default branch (usually `main`).
- [ ] Enable GitHub Pages (branch: `main`, folder: `/ (root)`).

How to push from your local repo (PowerShell)
--------------------------------------------
Open PowerShell in your project folder and run:

```powershell
# check status
git status

# stage files
git add index.html README.md .nojekyll

# commit
git commit -m "Add README and enable GitHub Pages"

# push to GitHub
git push origin main
```

Enable Pages in GitHub UI
-------------------------
1. Go to: https://github.com/israelessien48-art/wdd130 (replace username if needed).
2. Click Settings → Pages.
3. Under "Build and deployment": choose Branch = `main`, Folder = `/ (root)` then Save.
4. Wait a minute, then visit:

   https://israelessien48-art.github.io/wdd130

Troubleshooting
---------------
- If you get a 404: confirm the repo name is exactly `wdd130` and that the repo is public.
- If your GitHub username is different, substitute it in the URL above.
- If Pages shows a build error in Settings → Pages, open the build log for details.

If you want, I can prepare a small commit for you (README + .nojekyll) — after you review, commit and push and tell me when it's pushed, I will re-check the Pages URL for you.
# WDD 130 Starting Template Repository
This repository is a starting template for students in WDD 130.