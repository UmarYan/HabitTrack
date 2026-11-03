# HabitFlow v0.2 — PWA

## Included in this increment
- Premium/Material-inspired responsive UI with Home, Habits, Insights, Calendar, Settings tabs
- IndexedDB persistence retained using the same database and store (`habitflow-db`, `habits`)
- Habit create/edit, archive/restore, search and filtering
- Boolean, quantity, duration tracking
- Weekday schedule configuration
- Daily completion and importance-weighted score indicators
- 30-day insight summary and visual heatmap
- Month calendar with date-level habit detail
- JSON backup export and additive restore (matching IDs replaced, unrelated records retained)
- Light, dark, and system theme controls
- PWA app shell cache bumped to v2

## Deploy
Serve over HTTPS or localhost for PWA service-worker/install support. Deploy folder contents to GitHub Pages or Cloudflare Pages.

## Notes / scope
- No cloud sync or account system.
- Browser notifications and reminder scheduling are not included in this increment.
- Advanced scoring settings, custom formulas, habit milestones and routines remain planned.
- Existing v0.1 habit records are retained because the IndexedDB schema/database remains compatible.
