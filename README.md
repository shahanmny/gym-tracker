# Gym Tracker — Hyperbolic Time Chamber

A single-page dumbbell hypertrophy tracker. 140 days, 20 weeks, 4 lifting days a week, 5 exercises a day, straight sets only.

Log the weight and reps for each set and the page works out the next session's target itself, based on a simple rule: hit the top of the rep range on every set and you jump to the next real dumbbell setting; improve but don't top out and you add a rep; stall at the same weight for two sessions running and you drop a setting.

## Files

- `index.html` — the whole app: markup, styles, and the progression logic, in one file.

## Program structure

| Weeks | Phase | Sessions |
|---|---|---|
| 1–6 | Block A | 24 |
| 7 | Deload (2 sets) | 4 |
| 8–13 | Block B | 24 |
| 14 | Deload (2 sets) | 4 |
| 15–20 | Block C | 24 |

## Data

Workout logs are stored separately from this source, in the hosted page's own database — this repo only tracks the program and app code, not logged sets.
