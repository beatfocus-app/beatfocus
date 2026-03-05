# BeatFocus

**Time tracking for music producers.**  
Stop losing hours in your DAW. BeatFocus helps you track your studio sessions, rate your focus, and see exactly how you work.

> Early Access v0.2.0

---

## What is BeatFocus?

BeatFocus is a desktop app built for music producers, artists, and studio engineers who want to take control of their creative time.

- **Start a session** — name what you're working on, pick a project, set your timer
- **Rate your focus** — Struggle / OK / Flow after every session
- **Track your history** — calendar view, filters, session log
- **See your analytics** — weekly activity, streak, ratings breakdown, top projects
- **Stay on top** — Always on Top mode keeps BeatFocus visible while you work in your DAW

---

## Features

| Feature | Status |
|---|---|
| Focus Timer (custom duration) | ✅ |
| Project Management | ✅ |
| Session Rating (Struggle / OK / Flow) | ✅ |
| Session Tags (Breakthrough, Stuck, Creative, Productive) | ✅ |
| History with Calendar View | ✅ |
| Analytics (Weekly, Streak, Ratings, Projects) | ✅ |
| Always on Top Toggle | ✅ |
| Keyboard Shortcuts (Space, ESC) | ✅ |
| Update Notifications | ✅ |
| 100% Local — no account, no cloud | ✅ |
| Windows Portable Build | ✅ |

---

## System Requirements

- Windows 10 or 11 (64-bit)
- ~330 MB disk space
- 4 GB RAM minimum
- No internet required (except for update checks)

---

## Privacy

All data is stored **locally on your device**.  
Nothing is sent to external servers except an optional update check
Debug logs are saved locally to `Documents/BeatFocus/errors.log`.

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Start / Pause Timer |
| `ESC` | Stop Timer / Close Modal / Close Panel |

---

## Installation Guide

**Installer (`BeatFocus-Setup.exe`)**
1. Download from Releases
2. Run the installer
3. If Windows warns you → click "More info" → "Run anyway"
4. Follow the setup wizard (~10 seconds)
5. Launch BeatFocus

**Portable (`BeatFocus-Portable.exe`)**
1. Download from Releases
2. Double-click — done. No installation needed.

---

## Changelog

### v0.2.0 — Current
- Always on Top toggle in Settings
- Floating "+" button in Projects panel
- Smoother UI transitions & timer pulse animation
- Custom modal dialogs (no native Electron dialogs)
- About modal with license info
- Portable build target (.exe)
- Various bug fixes

### v0.1.1
- Bug fixes & performance improvements
- Better statistics display

### v0.1.0 — Initial Release
- Core timer with progress ring
- Project management
- Session ratings & tags
- Analytics with Chart.js
- History with calendar view
- First-launch ToS/Privacy modal
- Local error logging

---

## Tech Stack

- [Electron](https://www.electronjs.org/) — Desktop framework
- HTML / CSS / JavaScript — UI
- [Chart.js](https://www.chartjs.org/) — Analytics charts
- localStorage — Local data storage
- electron-builder — Build & packaging

---

## Legal

© 2026 MRJ Production. All rights reserved.  

Website: [beatfocus.app](https://beatfocus.app)  
Support: support@beatfocus.app
