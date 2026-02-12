# Juracka Design Co. Website

This is a static website and can be launched for free with GitHub Pages.

## One-click-ish launch

1. Push this repo to GitHub.
2. Click this button in your GitHub repo: **Actions → “Deploy static site to GitHub Pages” → Run workflow**.
3. Open your live site at:

`https://<your-username>.github.io/<repo-name>/`

> You do **not** need to buy a domain.

## First-time setup (once)

In your repo on GitHub:
- Go to **Settings → Pages**
- Set **Source** to **GitHub Actions**

## Push commands

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

## Local preview

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.
