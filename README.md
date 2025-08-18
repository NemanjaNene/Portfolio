# Portfolio Starter

A minimal, clean HTML/CSS starter for a personal portfolio. No frameworks, no build step.

## How to use
1. Edit `index.html` and `styles.css` with your info.
2. Open `index.html` in your browser to preview.

## Deploy options

### A) GitHub Pages (fastest)
1. Create a repo on GitHub, e.g. `nemanja-portfolio`.
2. Push these files (see commands below).
3. In the repo: Settings → Pages → Build and deployment → Source: **Deploy from a branch**.
4. Select branch: **main** and folder: **/(root)**, then **Save**.
5. Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

### B) Netlify
- Drag-and-drop the folder on https://app.netlify.com/drop or connect the Git repo.
- Netlify auto-deploys on each push.

### C) Vercel
- Import your GitHub repo at https://vercel.com/new and deploy. No config needed for static sites.

## Git commands (first time)

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Update later
Edit files and commit again:
```bash
git add -A
git commit -m "Update content"
git push
```

