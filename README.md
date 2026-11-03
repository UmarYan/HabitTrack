# Loop-like Habit Tracker PWA — V0.4

This update rebuilds the visual structure from the user-provided Loop Habit Tracker screenshots: grey habit overview toolbar and compact weekly status columns; orange habit detail toolbar; overview metrics, score/history canvases, month calendar tiles, best-streak list and frequency rows.

## Features
- Habit create/edit/delete, icon/emoji, color, description, schedule (daily/weekdays/weekends/custom/3x weekly), reminder-time field, target/unit
- Four recent daily columns with cycle states: unmarked → complete → skipped → unmarked
- Habit detail analytics with Score, History, Calendar, Best streaks and Frequency
- Overview score, Month/Year estimates and total completed count
- JSON backup/import, CSV export, localStorage persistence and PWA service-worker caching

## Run
Serve this folder over HTTPS or localhost, then install from your browser menu. Static hosting (GitHub Pages, Netlify, Cloudflare Pages) is suitable.

## Accuracy notes
This is a custom PWA UI/behavior implementation based on the supplied screenshots. Score calculation and chart data are approximations, not the verified original Loop algorithms. Native Android widgets and reliable background notification scheduling are not available in this PWA. Android/browser visual verification has not been performed in this environment.
