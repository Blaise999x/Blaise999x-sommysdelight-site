# Sommys Delight Website

This repository contains the static website for Sommys Delight.

## Deployment Steps

1. Create a GitHub repository called `sommysdelight` (or any name).
2. Add this folder as a git repo and push to GitHub:
   ```powershell
git remote add origin https://github.com/<your-username>/sommysdelight.git
git branch -M main
git push -u origin main
```
3. In GitHub repository settings, enable GitHub Pages from the `main` branch.
4. Add DNS records for `sommysdelight.com` pointing to GitHub Pages, and configure `www` as a CNAME to `sommysdelight.com`.

## Local Preview

Open `index.html` in a browser or use a local server:
```powershell
python -m http.server 8000
```

