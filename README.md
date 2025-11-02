# Portfolio

This repository contains a static portfolio website (HTML, CSS, JS). It is configured to deploy to GitHub Pages.

What I added:
- `README.md` — this file
- `.gitignore` — ignores common files
- `.github/workflows/pages.yml` — GitHub Actions workflow to deploy the site to GitHub Pages on push to `main`

How to publish (quick):
1. Create a new repository on GitHub (via the website or `gh repo create`).
2. Add the GitHub remote and push your `main` branch:

   ```powershell
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. The included GitHub Pages workflow will automatically deploy your site from the repository root on pushes to `main`.

If you prefer not to use Actions, you can also enable GitHub Pages in the repository Settings and serve directly from the `main` branch.

If you want, I can guide you through creating the remote repo and pushing (requires your input or the GitHub CLI / credentials).

---
Generated on: 2025-11-02
