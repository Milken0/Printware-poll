# Printware Client Feedback Poll

A smart, mobile-friendly feedback poll for Printware Company Limited.
Clients select what service they received, and are only shown rating
categories relevant to their experience.

---

## 🚀 Deploy to Vercel (Recommended — Free)

### Step 1 — Install Node.js
Download and install from: https://nodejs.org (choose the LTS version)

### Step 2 — Install dependencies
Open a terminal/command prompt inside this folder and run:
```
npm install
```

### Step 3 — Test locally (optional)
```
npm run dev
```
Then open http://localhost:5173 in your browser to preview.

### Step 4 — Push to GitHub
1. Create a free account at https://github.com
2. Create a new repository called `printware-poll`
3. Upload all files in this folder to that repository

### Step 5 — Deploy on Vercel
1. Create a free account at https://vercel.com
2. Click **"Add New Project"**
3. Connect your GitHub account and select the `printware-poll` repo
4. Leave all settings as default and click **"Deploy"**
5. Vercel gives you a live URL like `printware-poll.vercel.app` ✅

---

## 📱 Share With Clients

- **QR Code**: Go to https://qr-code-generator.com, paste your Vercel URL, and download a QR code to print at your branches.
- **WhatsApp / Email**: Send the link directly to clients after a transaction.
- **Tablet at counter**: Open the URL on a tablet at your service desk.

---

## 🗂 Project Structure

```
printware-poll/
├── index.html          # Page shell
├── package.json        # Dependencies
├── vite.config.js      # Build config
├── public/
│   └── favicon.svg     # Browser tab icon
└── src/
    ├── main.jsx        # App entry point
    ├── App.jsx         # Poll component (edit here)
    └── index.css       # Global styles
```

---

## ✏️ Customising the Poll

All changes are made in `src/App.jsx`:

- **Add/remove service types** → edit the `SERVICE_TYPES` array
- **Add/remove rating dimensions** → edit the `ALL_RATINGS` array
- **Change colours** → search for `#F5A623` (gold) or `#0D0D0D` (background)

---

Printware Company Limited © 2025
