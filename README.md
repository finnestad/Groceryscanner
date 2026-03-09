# Grocery Scanner

A mobile-friendly barcode scanning app for tracking grocery items and shop totals.

## Features
- 📷 Camera barcode scanning (front & back camera toggle)
- ✏️ Manual barcode entry fallback
- 🧺 Running cart total with line items
- 📦 Persistent product database (saved in browser)
- 🗑 Batch delete products
- ⬇️ Export shop data to CSV
- ✓ Complete shop summary

## Setup
This app runs entirely in the browser — no server or backend required.

## Usage
1. Open the app over HTTPS (GitHub Pages)
2. Tap **Start Scanner** and allow camera access
3. Scan a barcode — if new, enter the item details once; they'll be remembered next time
4. Watch the running total update live
5. Tap **Complete Shop** to review or **Export CSV** to download your shop data

## Hosting on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app will be live at `https://yourusername.github.io/your-repo-name`

> ⚠️ Camera access requires HTTPS. GitHub Pages provides this automatically.
