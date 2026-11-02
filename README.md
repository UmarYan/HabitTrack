# Habit Tracker — Extensive PWA Prototype

A substantial installable-web prototype with Loop-like minimalist interaction patterns. This is an independent implementation, not the official Loop app or a pixel-perfect Android clone.

## Included screens
- Home/dashboard: date-strip/week navigation, selected-date checkmarks, custom/name/score sort
- Habit detail: strength score, current/best streak, completion rate, recent calendar, 12-week chart, date notes, archive/delete
- Statistics: habit selection, 30/90/365/all range controls, score, streaks, completion rate, chart, heatmap and recent activity
- History: month calendar, date-specific status editor (done/skip/clear/value), notes, monthly summaries
- Create/Edit habit: Boolean and measurable tracking; at-least/at-most goals; daily, weekday, quota/week, quota/month, alternate, weekly and biweekly schedules; colors; reminder metadata and days
- Archived habits: restore or delete
- Settings: light/dark theme, week start, day rollover setting, confetti setting, notification permission prompt, JSON backup import/export, CSV export and reset
- LocalStorage persistence and offline PWA service worker

## Run/install
Use an HTTP static server to serve this folder (service worker/PWA install needs HTTPS or localhost). On Android Chrome, open the served app and choose Install app / Add to Home screen.

## Current limitations (honest scope)
- Web PWA is not native Android APK.
- Reminders are saved as metadata; reliable scheduled Android notifications with Done/Skip/Snooze action need native Android AlarmManager/WorkManager + notification action receiver.
- PWA home-screen widgets aren't implemented.
- Exact Loop data schema, exact score algorithm and full SQLite/CSV interoperability aren't guaranteed; score/streak calculations are prototype approximations.
- Some quota schedules are simplified, not a complete frequency engine.
- No drag-and-drop habit reorder yet; sort choices are implemented.
- No automated test suite or browser/device test has been run; syntax validation was performed where available.

## License / reference
Loop Habit Tracker is GPL-3.0 open source. Official reference: https://github.com/iSoron/uhabits and https://play.google.com/store/apps/details?id=org.isoron.uhabits.
This prototype was independently written and does not bundle Loop source or assets.