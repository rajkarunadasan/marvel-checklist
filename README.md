# 🦸 Marvel Universe Checklist — Android App

A fully offline Progressive Web App (PWA) that installs on your Android phone like a real app.

---

## ⚡ Quickest Way: GitHub Pages (Free, 5 mins)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `marvel-checklist`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. Click **uploading an existing file**
2. Upload ALL files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png` ← put icons in a folder named `icons`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Under "Branch", select **main** and click **Save**
3. Wait ~60 seconds, then your app is live at:
   `https://YOUR-USERNAME.github.io/marvel-checklist/`

### Step 5 — Install on Android
1. Open **Chrome** on your phone
2. Go to your GitHub Pages URL
3. Tap the **⋮ menu** (top right) → **Add to Home screen**
4. Tap **Add**
5. Done! The app appears on your home screen like a real app 🎉

---

## 📦 What's included
- `index.html` — the entire app (150+ Marvel entries, all logic)
- `manifest.json` — makes it installable as an app
- `sw.js` — service worker for offline support
- `icons/` — app icons (192px and 512px)

## 💾 Data storage
All your watch progress is saved in your phone's **localStorage** — it persists between sessions and works completely offline. Nothing is sent to any server.

---

## Alternative: Host locally with a USB cable
If you don't want GitHub, you can run a local server and access it on your phone via your home WiFi:
```
python3 -m http.server 8000
```
Then open `http://YOUR-PC-IP:8000` in Chrome on your phone and add to home screen.
