# Gladiator Patch — Landing Page

Official landing page for **Gladiator Patch** — a PES 6 patch for the 2008/09 season.

🌐 Live site: `https://<your-github-username>.github.io/GladiatorPatch/`

## What's here

- `index.html` — Landing page (English)
- `css/style.css` — Styles
- `assets/` — Logo images

## Deploy to GitHub Pages (free)

### 1. Create a GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `GladiatorPatch` (or `gladiatorpatch`)
3. Set it to **Public**
4. Do **not** add README/gitignore (we already have them)
5. Click **Create repository**

### 2. Push this project

```bash
cd /path/to/GladiatorPatch
git init
git add .
git commit -m "Initial landing page"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/GladiatorPatch.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` → folder: `/ (root)`
4. Click **Save**
5. Wait ~1 minute — your site will be live at:
   `https://<YOUR_USERNAME>.github.io/GladiatorPatch/`

### 4. (Optional) Custom domain later

When you buy `gladiatorpatch.com`:
1. Add a `CNAME` file with `gladiatorpatch.com` inside
2. Point your domain's DNS to GitHub Pages (Settings → Pages → Custom domain)

## Links

| Platform  | URL |
|-----------|-----|
| Telegram  | https://t.me/GladiatorPatch |
| YouTube   | https://www.youtube.com/channel/UCMApDrHoBN6MyuhTaV2KQHA |
| Facebook  | https://www.facebook.com/gladiatorpatch/ |
| Evoweb    | https://evoweb.uk/threads/pes-6-gladiator-patch-2008-09-season-the-final-chapter-coming-soon.89756/ |

## Local preview

Open `index.html` in your browser, or:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```
