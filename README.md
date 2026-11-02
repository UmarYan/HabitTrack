# Loop-like Habit Tracker PWA (starter)

Offline-first browser/PWA habit tracker with a compact Loop-inspired weekly grid.

## Run
Serve this directory on HTTPS or localhost (service worker requires a secure context). GitHub Pages/Netlify/Cloudflare Pages work. Open `index.html`; install from the browser menu.

## Included
- Habit add/edit/delete, color and descriptions
- Daily, weekdays, weekends, custom weekdays and 3×/week schedule options
- Weekly checkmarks (complete / skip / clear)
- LocalStorage persistence
- Strength score overview, recent history
- JSON backup restore and CSV checkmark export
- Installable manifest and offline service worker

## Limitations
This is an independently implemented PWA prototype, not the full native Loop Android app. Reminder permissions are requested but reliable timed background delivery, Android widgets, SQLite export and native integrations are not implemented in a PWA. Habit strength is a simple weighted approximation, not Loop's original scoring algorithm.

## Licensing note
This prototype's code is newly written and does not bundle Loop source. If you later port or modify Loop's GPL-3.0 code, preserve copyright and license notices and comply with GPLv3 when distributing the derivative. Loop source: https://github.com/iSoron/uhabits
