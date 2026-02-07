# Weekly Tasks

A lightweight, mobile-first weekly task tracker PWA — built to replace notebook task lists.

![Weekly Tasks](https://img.shields.io/badge/PWA-ready-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Quick add** — type and hit Enter to add tasks instantly
- **Day assignment** — assign tasks to specific days (Mon–Sun) or keep them general
- **Week navigation** — browse past and future weeks, plan ahead
- **Rollover** — carry incomplete tasks forward to the next week with full tracking
  - Source week shows "→ Moved to next week" with faded styling
  - Target week shows "↻ Rolled over" with undo support
- **Progress tracking** — visual progress bar per week
- **Swipe navigation** — swipe left/right to change weeks on mobile
- **Offline-ready** — all data stored in localStorage, no server required
- **Add to Home Screen** — PWA meta tags for full-screen app experience on iOS and Android

## Demo

Deploy to GitHub Pages and open on your phone to try it out.

## Getting Started

### Option 1: GitHub Pages (recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your app will be live at `https://<username>.github.io/weekly-tasks/`
5. Open the URL on your phone in Safari and tap **Share → Add to Home Screen**

### Option 2: Open locally

Just open `index.html` in any browser — everything runs client-side.

## Tech Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies
- Single file (`index.html`), no build step
- localStorage for persistence
- PWA manifest for home screen install

## Project Structure

```
weekly-tasks/
├── index.html      # The entire app (single file)
├── README.md       # This file
└── LICENSE         # MIT License
```

## License

MIT
