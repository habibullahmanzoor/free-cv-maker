# 📄 Free CV Maker by Dr Habib

A **free, privacy-first CV builder** that runs entirely in your browser. Build a professional CV with **9 templates** (including **Europass** and an ATS-friendly plain layout), style it to match your taste, and download it as a PDF. **Your data never leaves your device** — no accounts, no servers, no tracking.

🔗 **Live demo:** `https://<your-username>.github.io/<your-repo-name>/`

---

## ✨ Features

- 🎨 **9 professional templates** — Timeline, Europass, Sidebar, Dark, Bold, Compact, Classic, Minimal, Plain ATS
- 🌍 **Europass format** — for European job applications
- 🤖 **ATS-friendly plain layout** — plain black & white, single column, read easily by Applicant Tracking Systems
- 🎯 **Live preview** — see your CV update as you type
- 📷 **Photo upload with crop & zoom** — circle or square, resizable
- 🎨 **Full design control** — accent colour, font pairing, text scale, section spacing, margins, A4 or US Letter
- 📑 **Auto page-break indicators** — dashed lines show where each new page begins
- 💾 **Auto-save** — everything stored in your browser's `localStorage`
- ↪️ **Undo / Redo** — `Ctrl/Cmd + Z`, `Ctrl/Cmd + Shift + Z`
- 📤 **Export / Import JSON** — back up and restore your CV
- 🖨️ **One-click PDF download** — uses your browser's native print-to-PDF
- 🧠 **Optional AI assistant** (OpenRouter) — proofread text and rewrite work highlights with the STAR method
- 📱 **Mobile-friendly** — Edit / Preview toggle on small screens
- 🔒 **100% client-side** — no backend, no analytics, no cookies

---

## 🖥️ Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts |
| AI (optional) | [OpenRouter API](https://openrouter.ai) |
| Storage | Browser `localStorage` |

**No build step. No dependencies. No `npm install`.** Just one `index.html` file.

---

## 🚀 How to Host on GitHub Pages

### 1. Create a GitHub account
Sign up at [github.com](https://github.com) if you don't have one.

### 2. Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it, e.g. `cv-maker`
3. Set visibility to **Public**
4. **Do not** initialise with a README
5. Click **Create repository**

### 3. Upload your files
You need exactly **two files** in the repo root:
- `index.html`
- `README.md`

**Web upload (easiest):**
1. On your repo page, click **Add file** → **Upload files**
2. Drag in `index.html` and `README.md`
3. Write a commit message like `Initial commit`
4. Click **Commit changes**

**Command line:**
```bash
git clone https://github.com/<your-username>/cv-maker.git
cd cv-maker
# copy index.html and README.md here
git add .
git commit -m "Initial commit: Free CV Maker"
git push origin main
