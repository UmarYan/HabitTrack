# HabitFlow v0.1 — PWA Starter

A foundational Android-first, local-first HabitFlow PWA.

## Included
- Responsive premium/Material-inspired dashboard
- IndexedDB habit persistence
- Boolean, quantity, and duration tracking
- Habit name, category, importance weight
- Daily progress ring and week visualization
- Light/dark theme toggle
- PWA manifest, SVG icon, service worker shell caching

## Run
Serve this folder using a local web server or deploy it to GitHub Pages / Cloudflare Pages.
Service workers and installability require HTTPS (or localhost). Opening `index.html` directly can still show the interface, but PWA features may not work.

## Current scope notes
- Navigation sections other than Home are placeholders.
- Quantity/duration records currently accept one daily value.
- This starter does not yet implement schedule management, reminders, advanced scoring, calendar, insights, export/restore, or cloud sync.
- The service worker caches the app shell; IndexedDB holds habit records.
