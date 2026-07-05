# Momentum 🔥

A premium, Apple-inspired habit, goal & focus tracker — in a **single HTML file**. No build step, no dependencies, no server, no account. All data stays in your browser (localStorage).

## Features

- **Today dashboard** — animated progress ring, current streak, weekly %, quote of the day, week strip
- **Habits** — emoji, color, category, daily/weekdays/weekly/monthly frequency, checkbox or numeric targets (water, pages, km…), reminders, notes
- **Statistics** — 20-week heatmap, daily completion chart, best-day-of-week analysis, consistency score
- **Goals** — milestones, deadlines, progress bars
- **Focus timer** — Pomodoro (auto-break), countdown, stopwatch, session history
- **Achievements** — streak badges, perfect week, confetti + sound on unlock
- **Dark / light / auto theme**, accent colors, reduced-motion support
- **Export / import** — JSON backup and CSV export
- Keyboard shortcuts: `N` new habit · `T` timer · `1–9` toggle today's habits

## Files

- `index.html` — the whole app
- `sw.js` — service worker (offline support + notification delivery)
- `manifest.json`, `icon.svg` — makes it installable as an app

## Use it

Just open `index.html` in any modern browser. That's it.

## Host it free on GitHub Pages

1. Create a new repository on GitHub
2. Upload **all four files** (`index.html`, `sw.js`, `manifest.json`, `icon.svg`)
3. Repo **Settings → Pages → Source: Deploy from a branch → main → / (root) → Save**
4. Your app is live at `https://<your-username>.github.io/<repo-name>/`

## iPhone setup (important for reminders)

1. Open your GitHub Pages URL in Safari
2. Tap **Share → Add to Home Screen** — this installs Momentum as an app
3. Open it from the Home Screen, go to **Settings → Notifications → Enable** and allow

Reminders fire while the app is open (or recently open on your Home Screen). iOS pauses web apps that are fully closed, so also keep an eye on the in-app reminder toasts.

> Data is stored on your device (localStorage + an IndexedDB backup copy) and survives closing the browser or restarting your phone. Use **Settings → Export data (JSON)** for an extra backup or to move between devices.

## License

Personal use. Original design and code — not affiliated with any existing app.
