# TrackMe — Personal Progress Dashboard

A lightweight browser-based self-tracking website built from the notebook system.

## Features
- 3 daily priorities
- Custom habits
- Daily completion score
- Focus time tracking
- End-of-day reflection
- 7-day analytics
- Habit consistency
- Long-term measurable goals
- Light/dark theme
- JSON export/import
- Browser localStorage persistence
- Responsive mobile layout

## Run it
Open `index.html` in a browser.

For best results, use a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Current data model
Everything is stored locally in the browser. No account or backend is needed for this MVP.

## Good next upgrades
- Supabase authentication + cloud database
- Cross-device sync
- Calendar view
- PWA install support
- Notifications/reminders
- Goal milestones
- Monthly analytics
