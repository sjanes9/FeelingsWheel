# Feelings Wheel — PWA Deployment Guide

## What's in this folder

| File | Purpose |
|------|---------|
| `index.html` | The main app (rename feelings-wheel.html → index.html) |
| `manifest.json` | Makes it installable as an app |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen, small) |
| `icon-512.png` | App icon (splash screen, large) |

---

## Deploy to GitHub Pages (free, ~10 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up for a free account if you don't have one.

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it something like `feelings-wheel`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. Click **uploading an existing file** on the repo page
2. Drag and drop ALL files from this folder:
   - `index.html` ← rename `feelings-wheel.html` to this first!
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

### Step 5 — Get your link
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/feelings-wheel/
```

---

## Install on iPhone
1. Open the link in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow at bottom)
3. Tap **Add to Home Screen**
4. Tap **Add** — it now appears as an app icon!

## Install on Android
1. Open the link in **Chrome**
2. Tap the **three dots** menu (top right)
3. Tap **Add to Home screen** or **Install app**
4. Tap **Install**

## Install on Desktop (Chrome/Edge)
1. Open the link
2. Look for the **install icon** (⊕) in the address bar
3. Click it and confirm — it opens as a standalone window

---

## Works offline
Once installed, the app works completely offline. Your journal entries are saved 
locally on your device and never sent to any server.

---

## Custom domain (optional)
If you own a domain (e.g. `myfeelings.app`), you can point it to GitHub Pages 
for free via the repo Settings → Pages → Custom domain.
