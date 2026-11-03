# HabitFlow v1.4 — Journal UI Repair

This release is based on the supplied HabitFlow v1.3 ZIP. It fixes the journal page form layout: each textarea is stacked beneath its label, full-width and styled consistently, with responsive sizing. Journal behavior and data storage are unchanged. The service-worker cache version is bumped to ensure updated CSS is fetched.

# HabitFlow v1.0 — Polish & Stability

HabitFlow is an installable, local-first habit tracking PWA.

## v1.0 stability and polish
- Expanded JSON backup schema (v2) includes theme, dashboard layout, and dashboard visibility preferences in addition to habits, scoring settings, daily goals, and journal entries.
- Restore performs a full preflight validation of the habit array and journal container before writing habit records, reducing risk of partial imports caused by malformed backup content.
- Restore accepts legacy backups with no preference bundle and retains merge behavior for matching habit IDs.
- JSON import size limit (25 MB) and clearer validation feedback.
- Export object URL cleanup delayed briefly to allow the browser download to begin.
- Added optional browser storage estimate display where supported.
- Service worker shell cache version bumped for release refresh; manifest version set to 1.0.

## Existing features
Habit management (boolean, quantity, duration), flexible weekday schedules, categories and icon/color customization, advanced scoring, skip days, daily goals and achievements, analytics, calendar history, reminders checked while app is open, themes, and date-based journal.

## Storage and limitations
Habit records use IndexedDB; preferences and journal entries use localStorage. Data stays in this browser/device unless the user exports a backup. Browser reminders are checked while the app is open; this PWA does not schedule operating-system background alarms. The journal is not encrypted. Storage estimate is browser-provided and may not reflect exact app-only usage.

## Validation
JavaScript syntax and ZIP integrity checks passed. Browser testing was not performed.
