# Full Body Workout PWA

A progressive web app — install it on your iPhone like a native app.

---

## Deploy in 3 steps

### 1. Push to GitHub
- Go to github.com → New repository → name it `workout-app` → Create
- Upload all files in this folder (index.html, manifest.json, sw.js, icon-192.png, icon-512.png)

### 2. Deploy on Vercel
- Go to vercel.com → Sign in with GitHub
- Click "Add New Project" → Import your `workout-app` repo
- Leave all settings as default → click Deploy
- Vercel gives you a URL like: `https://workout-app-xyz.vercel.app`

### 3. Install on iPhone
- Open Safari on your iPhone (must be Safari, not Chrome)
- Go to your Vercel URL
- Tap the Share button (box with arrow at bottom)
- Tap "Add to Home Screen"
- Tap "Add" — done!

The app icon appears on your home screen and opens full screen with no browser bar, just like a native app. It also works offline.

---

## Files
- `index.html` — the full app
- `manifest.json` — PWA config (name, icon, display mode)
- `sw.js` — service worker (enables offline use)
- `icon-192.png` — home screen icon
- `icon-512.png` — splash screen icon
