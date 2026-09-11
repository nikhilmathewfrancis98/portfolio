# Nikhil Mathew Francis — Portfolio

Personal portfolio site built with vanilla HTML + CSS.

## Deploy to GitHub Pages (5 minutes, free)

### Step 1 — Create the repo

1. Go to https://github.com/new
2. Repo name: **`nikhilmathewfrancis98.github.io`** (must match your GitHub username exactly + `.github.io`)
3. Visibility: **Public**
4. Don't add README/gitignore/license — just create it empty.

### Step 2 — Push the file

```bash
cd c:\lms\WorkArea\portfolio
git init
git add index.html README.md
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/nikhilmathewfrancis98/nikhilmathewfrancis98.github.io.git
git push -u origin main
```

### Step 3 — Enable Pages (usually auto-enabled for `username.github.io` repos)

1. Go to repo → **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` / `/ (root)` → Save

### Step 4 — Visit your live site

In 1–2 minutes: **https://nikhilmathewfrancis98.github.io**

Add this URL to:
- LinkedIn → Contact info → Website
- Naukri → Profile → Other info → Web profile
- Email signature
- Top of your resume

## Customizing

The whole site is in `index.html` — edit it directly. Sections are clearly commented (`<!-- HERO -->`, `<!-- ABOUT -->`, etc.).

To change colors, edit the `:root` CSS variables at the top of the `<style>` block.

## Local Preview

Just open `index.html` in any browser. No build step, no dependencies.
