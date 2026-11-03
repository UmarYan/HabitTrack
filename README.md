# Loop-like Habit Tracker PWA (starter)

Offline-first browser/PWA habit tracker with a compact Loop-inspired weekly grid.

## Run
Serve this directory on HTTPS or localhost (service worker requires a secure context). GitHub Pages/Netlify/Cloudflare Pages work. Open `index.html`; install from the browser menu.

## Version 0.3 additions
- Monthly habit calendar with previous/next month navigation and scheduled/completed/skipped markers
- Current-day highlighting and calendar legend
- Safer import validation; service-worker cache version bumped

## Included
- Habit add/edit/delete, color and descriptions
- Daily, weekdays, weekends, custom weekdays and 3×/week schedule options
- Weekly checkmarks (complete / skip / clear)
- LocalStorage persistence
- Strength score overview, recent history
- JSON backup restore and CSV checkmark export
- Installable manifest and offline service worker

## Validation
- JavaScript syntax checked with Node.js
- ZIP archive integrity checked
- Browser interaction testing was not performed in this environment

## Limitations
This is an independently implemented PWA prototype, not the full native Loop Android app. Reminder permissions are requested but reliable timed background delivery, Android widgets, SQLite export and native integrations are not implemented in a PWA. Habit strength is a simple weighted approximation, not Loop's original scoring algorithm.

## Licensing note
This prototype's code is newly written and does not bundle Loop source. If you later port or modify Loop's GPL-3.0 code, preserve copyright and license notices and comply with GPLv3 when distributing the derivative. Loop source: https://github.com/iSoron/uhabits

## v0.2 iteration
- Added a habit detail view opened by tapping a habit name.
- Detail view shows weighted strength, a basic current streak, 30-day completion rate, calendar-style recent checkmarks, and schedule summary.
- Habit editing is available from the detail view.

This remains a prototype: the streak and strength calculations are intentionally approximate and are not claimed to match Loop's exact algorithms.
