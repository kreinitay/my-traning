# Train & Play

Nitay's training + basketball app:
- Plans: Hoops, Hands & Legs, Pull-Ups, Jump High, Push-Ups
- Basketball log, season schedule, tests and coach notes
- Basketball: shot chart, player card, season goals, 4 challenges (free throws, threes, right-hand layups, around the world), opponent notes, game-day mode, 7 tests on test days A and B (6 a year) + mini tests (all 7 twice a year), records wall
- Journal (with Daylio-style activities and Year in Pixels), food log
- School: timetable, exams + study plans, homework, past grades and targets
- Life: water, stretch + warm-up timer, screen time, bedtime, injuries, height & reach, savings goals
- Week & month page: what's coming, totals, pop-ups, countdowns, Wrapped
- Streak board, month in photos, notification options
- Search, quick-add button, weekly auto backup
- Calendar and badges

It's a plain website with no build step, so it works on Netlify straight away.

## Files (all in one folder, no subfolders)
- `index.html`: the whole app
- `sw.js`: lets it work offline
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: app name and icon
- `netlify.toml`: Netlify settings
- `README.md`: this file

## Update on GitHub + Netlify
1. Open your repository on GitHub → **Add file → Upload files**.
2. Drag in all the files → **Commit changes**.
3. Netlify updates the site by itself in about a minute.
4. On the phone, close the app and open it again (twice if it still shows the old version).

## Put it on your phone like an app
Open your Netlify link in Chrome → **⋮ → Add to Home screen / Install app**.

## Login on several devices
Settings → **Account & sync** → follow the 5 steps (free Firebase).
After that, log in with the same account on every device.

## Moving your progress without an account
Progress tab → **Copy backup**, then on the other device → **Restore** and paste.
