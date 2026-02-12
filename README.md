# Juracka Design Co. Website

This site is a plain static website (`index.html` + assets), so you can host it **for free**.

## Launch for free with GitHub Pages (recommended)

### 1) Push this repo to GitHub
```bash
git remote add origin https://github.com/<your-username>/juracka_design_co.git
git branch -M main
git push -u origin main
```

### 2) Turn on GitHub Pages
1. Open your repo on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Save.

### 3) Your free URL
Your site will publish at:

`https://<your-username>.github.io/juracka_design_co/`

No domain purchase required.

---

## Important for free hosting
- This repo now uses the default GitHub Pages URL setup.
- If you later buy a custom domain, you can add a `CNAME` file back.

---

## Local preview
Run locally before publishing:

```bash
python3 -m http.server 4173
```

Then open:

`http://localhost:4173`
