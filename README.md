# Train & Play

Nitay's training + basketball app:
- Plans: Hoops, Hands & Legs, Pull-Ups, Jump High, Push-Ups
- Basketball log, season schedule, tests and coach notes
- Journal, food log, school timetable + exams
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
