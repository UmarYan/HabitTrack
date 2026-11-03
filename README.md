# HabitFlow v0.3 — Advanced Scoring Increment
- Configurable completion (7-day), consistency (30-day), recency (30-day exponential decay), and streak score weights; normalized automatically
- Importance-weighted overall advanced score
- Streak milestones: 7, 14, 30, 60, 100 days
- Skip-today action: excluded from aggregate daily scoring and neutral in streak progression
- Score configuration included in JSON backup and restore
- IndexedDB database/store preserved; added fields are optional
- Service worker shell cache v3
Verification: Node JS syntax and ZIP integrity passed; browser testing not performed.
