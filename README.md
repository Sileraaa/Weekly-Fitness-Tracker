# 🏔 Nourishment — PWA Setup Guide

A Skyrim-themed weekly nutrition tracker that installs as a native app on Android.

## Files
```
index.html    ← Main app (everything in one file)
manifest.json ← PWA identity & install config
sw.js         ← Service worker (offline support)
icon-192.png  ← App icon (home screen)
icon-512.png  ← App icon (splash screen)
```

---

## 🚀 Deploy to GitHub Pages (Free, 5 minutes)

### Step 1 — Create a GitHub repo
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **New repository**
3. Name it: `nourishment` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files
1. On the repo page, click **"uploading an existing file"**
2. Drag and drop ALL 5 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under "Source", select **Deploy from a branch**
3. Branch: `main` / Folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then your URL appears:
   `https://YOUR-USERNAME.github.io/nourishment/`

---

## 📱 Install on Android

1. Open **Chrome** on your Android phone
2. Go to your GitHub Pages URL
3. Chrome will show an **"Add to Home Screen"** banner automatically
   — OR — tap the ⋮ menu → "Add to Home Screen"
4. Tap **Add** → Done! 🎉

The app will appear on your home screen with the golden rune icon,
open fullscreen with no browser UI, and work **fully offline**.

---

## 💾 Data Storage
Your data is saved in the browser's `localStorage` — it persists
across sessions and app restarts. It's private to your device.

---

## ✦ Features
- Track daily calories, protein, fiber & weight
- Live remaining macro banners (kcal, protein, fiber needed per day)
- Weekly averages with rune progress bars
- Complete week → saves to Chronicle with Elder Scrolls remarks
- Trend charts across completed weeks
- Skyrim-style dark fantasy UI with aurora borealis background
- Fully offline after first load
