# Baby Twins Log

Single-file, offline-friendly daily log for **Twin A & Twin B**. Track feeds, diapers, sleep, notes — plus **mom’s pump (oz/min)**. Saves to your browser (LocalStorage), exports CSV, and prints cleanly.

**Live site:** https://marthaescudero.github.io/Baby-Twins-Log/

## Features
- Twin A/B entries with time, feed (type/oz/min), **pump (oz/min)**, diaper (W/S/B), sleep (start–end), notes
- **LocalStorage** persistence (data stays on your device)
- **Export CSV**, **Print**, and **Clear Day**
- Mobile-friendly UI (Tailwind via CDN)

## How to use
1. Open the live site (or double-click `index.html` locally).
2. Pick the date → add entries for Twin A/B.
3. Use **Export CSV** to download a daily backup.
4. **Print** for a paper copy if needed.

> Privacy: All data is saved only in your browser’s LocalStorage. Clearing site data or using a different device/browser will not share the data between them.

## Deploy / Update (GitHub Pages)
This repo is a single page app (`index.html`).

- **First time:** Settings → **Pages** → *Deploy from a branch* → `main` + `/ (root)` → **Save**.
- **Update the site:** Replace `index.html` in the repo and **Commit**. Pages redeploys automatically.

## Optional: Netlify (drag & drop)
1. Put `index.html` in a folder (e.g., `twins-daily-log`).
2. Go to https://app.netlify.com/drop and **drag the folder** in.
3. Rename the site in **Site settings → Site details → Change site name**.

## Tech
- React 18 (UMD) + Tailwind via CDN
- No build step required; works completely offline as a static file

## Troubleshooting
- **404 on Pages?** Re-check Settings → Pages: `main` + `/ (root)`. Wait ~1 minute and refresh.
- **Changes not showing?** Hard refresh (⌘⇧R / Ctrl+F5) or clear cache.
- **Data missing on another device?** Expected — LocalStorage is per device/browser.

---

**Made with 💚 for night-shift caregivers.**
