# 📊 HC/PG SA Monthly Report (PWA)

A simple Progressive Web App (PWA) for tracking daily and monthly reports of HC/PG SA performance.

---

## 🚀 Features

- 📅 Daily data entry per store
- ✏️ Edit existing entries
- 📊 Automatic monthly totals
- 📦 Grouped monthly reports (with subtotal per month)
- 📱 Installable as mobile app
- 📴 Offline support (cached app shell)
- 🖼 Export daily report as PNG

---

## 🛠 Tech Stack

- HTML / CSS / JavaScript
- Firebase Firestore
- Service Worker (PWA)
- html2canvas (for PNG export)

---

## 📦 Installation

1. Upload files to your hosting (Firebase Hosting recommended)
2. Ensure these files exist:
   - index.html
   - sw.js
   - manifest.json
   - /icons/icon-192.png
   - /icons/icon-512.png

3. Enable HTTPS (required for PWA)

---

## ⚙️ Service Worker

- Caches core app files
- Enables offline access
- Auto updates when cache version changes

To force update:
