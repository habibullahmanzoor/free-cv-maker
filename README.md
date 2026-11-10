<!-- BADGES -->
<div align="center">

# 📄 Free CV Maker by Dr Habib

### Build a professional CV in minutes — 100% in your browser, 100% free, 100% private.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with CSS](https://img.shields.io/badge/Made%20with-CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub Pages Ready](https://img.shields.io/badge/GitHub%20Pages-Ready-success)](https://pages.github.com/)

[**Live Demo**](#-live-demo) · [**Features**](#-features) · [**Quick Start**](#-quick-start) · [**Deploy**](#-deploy-to-github-pages) · [**FAQ**](#-faq)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Live Demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Features](#-features)
  - [Templates](#-9-professional-templates)
  - [Editing Experience](#-editing-experience)
  - [Design & Styling](#-design--styling)
  - [AI Assistant](#-ai-assistant-optional)
  - [Data & Privacy](#-data--privacy)
- [Quick Start](#-quick-start)

---

## 🎯 About

**Free CV Maker by Dr Habib** is a modern, single-file CV builder that runs entirely in your browser. It was built out of frustration with existing CV builders that:

- 💸 **Charge subscription fees** — often $10–$30/month just to *download* your own CV
- 🔐 **Require accounts** — handing over your personal data to companies you don't know
- 🐌 **Force watermarks** — unless you upgrade to a premium plan
- 📡 **Track everything** — analytics, ad networks, and third-party scripts on every keystroke
- 🖨️ **Break in print** — PDFs that don't match the on-screen preview

This project does **none of that**. It's:

- ✅ **Completely free** — no paywalls, no trials, no upgrades
- ✅ **Account-free** — no signup, no login, no email required
- ✅ **Watermark-free** — download clean PDFs immediately
- ✅ **Tracker-free** — no analytics, no ad networks, no third-party scripts
- ✅ **Print-accurate** — the PDF matches the preview (with one checkbox, see below)
- ✅ **Yours** — the entire app is one HTML file you can inspect, modify, and self-host

The whole app is **one file**: `index.html`. No backend. No database. No build step. No `node_modules`. Just open it in a browser and start building.

---
## ✨ Features

### 🎨 9 Professional Templates

Every template is a fully separate layout — not just a colour swap. Each is designed for a different career context:

| Template | Best For | Description |
|----------|----------|-------------|
| **Timeline** | Designers, product people | Vertical accent line with date markers — visually distinctive and modern |
| **Europass** | EU job applications | Recognisable European format with tinted header and structured sections |
| **Sidebar** | Multi-skill profiles | Two-column layout with photo, contact, and skills in the sidebar |
| **Dark** | Creative & tech roles | Dark right-hand column, bold name treatment, accent-coloured section rules |
| **Bold** | Sales, marketing, leadership | Colour-blocked header with strong typographic hierarchy |
| **Compact** | Dense CVs, long careers | Two-column main body with aside for education, skills, and languages |
| **Classic** | Law, academia, finance | Traditional centred header with small-caps section titles |
| **Minimal** | Modern portfolios, UX | Very clean, generous whitespace, numbered sections |
| **Plain ATS** | Applying through job portals | Plain black & white, single column, no colour — maximises parsing accuracy |

Every template is **live-rendered with your own data** in the template picker — so you compare your actual CV across all 9 layouts before choosing.

### 📝 Editing Experience

- **Section quick-jump bar** — sticky bar at the top of the editor lists every section. Click to jump straight to it.
- **Add/remove/reorder sections** — reorder the whole CV with `↑` / `↓`, hide sections with the eye icon, delete custom sections
- **Collapsible entries** — click any entry header to fold it away; collapse all entries in a section with the ⇕ button
- **12 section presets** — Certifications, Publications, Awards, Volunteering, Teaching, Grants, Conferences, Courses, Memberships, Interests, Driving licence, References — plus a blank custom section
- **Smart field labels** — the form adapts to the section name (a "Certification" section asks for title, year, and issuer; a "Reference" section asks for name, position, and contact)
- **Duplicate entries** — one click to clone any work, education, skill, project, or language entry
- **Delete with confirm** — no accidental deletions
- **Undo / Redo** — full history with `Ctrl/Cmd + Z`, `Ctrl/Cmd + Shift + Z`, up to 60 steps
- **Auto-save** — every keystroke is saved to `localStorage` within 420ms
- **Saved status indicator** — the dot next to "Saved" shows saving state (idle, saving, error)

### 🎨 Design & Styling

- **Accent colour** — 6 curated presets + a full custom colour picker
- **Font pairing** — 11 curated pairings (heading + body font combinations)
- **Text scale** — 85% to 115% to fit more or less content per page
- **Section spacing** — 80% to 140% for tighter or airier layout
- **Page margin** — 10mm to 30mm
- **Paper size** — A4 (210 × 297 mm) or US Letter (216 × 279 mm)
- **Photo controls** — show/hide toggle, circle/square shape, 14–40mm size slider
- **Photo crop tool** — drag to move, scroll wheel or slider to zoom, choose shape, apply
- **Live design updates** — every change re-renders the preview instantly

### 📄 Page & Print Management

- **Dashed page-break indicators** — a dashed line and "Page 2" label appear where the content overflows to the next page
- **Page count estimate** — the header bar shows roughly how many pages your CV takes
- **Zoom controls** — `+` / `−` buttons, plus a **Fit** button to fit the page to the window width
- **Resizable editor panel** — drag the divider between the editor and preview to make either side wider (double-click to reset)
- **Print-accurate margins** — the `@page` margin matches the on-screen margin so the PDF looks like the preview
- **Full-bleed templates** — Bold, Sidebar, and Dark templates have zero page margin for edge-to-edge colour blocks

### 🧠 AI Assistant (Optional)

The AI is **entirely optional** — every other feature works without it. It's a convenience for people who want a writing boost.

**Two AI features:**

1. **Proofread & strengthen** — available on any paragraph or bullet-list field (look for the small **AI** chip on the field label). It returns:
   - A cleaned-up version (grammar, spelling, clarity fixed — facts preserved)
   - 2–4 short tips for making that section stronger in a CV

2. **Rewrite with STAR** — available on every work entry (the "Rewrite highlights with STAR" button). It converts your existing bullets into achievement-focused bullets following the Situation-Task-Action-Result framework, with strong action verbs and measurable outcomes.

**AI behaviour details:**

- Uses [OpenRouter](https://openrouter.ai) with the `openrouter/free` model by default
- **Never** invents facts — the prompt explicitly forbids it
- **Never** uses em-dashes or en-dashes (a common AI tell)
- Uses simple English, short sentences
- Retries automatically up to 2 times if the model returns an empty response
- Your key is stored **only in your browser's `localStorage`**
- You can review the AI's suggestion side-by-side with the original, edit it inline, and only click **Accept** if you like it

**Enabling AI:**

1. Get a free key at [openrouter.ai/keys](https://openrouter.ai/keys)
2. In the app: **How to** → scroll to **Step 7** → paste your key → **Save**
3. That's it — AI buttons are now live

### 💾 Data & Privacy

- **Auto-save** — every change is saved to `localStorage` (key: `vitae.cv.v19`)
- **Export** — download the entire CV as a `.json` file (useful for backups)
- **Import** — load any previous `.json` export, including on a different browser or device
- **Undo after clear** — pressing Clear doesn't erase history; press `Ctrl+Z` to bring it back
- **Zero backend** — the app never makes any network request except to Google Fonts (for fonts) and OpenRouter (only when you click an AI button)
- **Zero analytics** — no Google Analytics, no Plausible, no Sentry, no tracking pixels
- **Zero cookies** — only `localStorage`

---

## 🚀 Quick Start

### Option 1 — Use it now

1. Download `index.html`
2. Double-click to open in your browser
3. Start building

That's it.

### Option 2 — Clone and run locally

```bash
git clone https://github.com/<your-username>/cv-maker.git
cd cv-maker

# Recommended: serve it over HTTP (avoids file:// quirks in some browsers)
python3 -m http.server 8000

# Open http://localhost:8000
