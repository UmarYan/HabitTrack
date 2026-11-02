# Loop Habit Tracker — PWA reconstruction (V1)

This is a Progressive Web App reconstruction aimed at matching Loop Habit Tracker's interaction model and mobile-first layout.

## Included
- Habit dashboard with weekly navigation and check-in states
- Habit creation/editing with schedule, measurable targets and reminders configuration
- Habit detail, score/streak indicators, date notes, history calendar and statistics views
- Archive/restore, JSON backup restore/export and CSV export
- Local-first browser storage, PWA manifest and service worker

## Install
Serve this folder over HTTPS (or localhost), open it in a supported browser, then use the browser's **Add to Home screen / Install app** option.

## Important fidelity limitations
This is a web reconstruction, not a direct conversion of Loop's native Android source. Native Android home-screen widgets, exact alarm scheduling, notification action buttons, SQLite database compatibility, and full pixel-perfect/native behavior are not available in this V1. The scoring/scheduling implementation is an approximation and should not be represented as identical to Loop until cross-checked against the source and test cases.

## Source reference and license
Loop Habit Tracker's upstream source is published by iSoron under GPL-3.0: https://github.com/iSoron/uhabits
This reconstruction does not bundle upstream source code. Review GPL and trademark terms before redistributing any derived work.
