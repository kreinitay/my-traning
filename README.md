# My Training

Nitay's training app: Pull-Up Plan, Jump High Plan and Push-Up Plan.
It's a plain website (no build step), so it works on Netlify straight away.

## Put it on Netlify (fastest)
1. Unzip this folder.
2. Go to https://app.netlify.com/drop
3. Drag the whole folder onto the page. Done — you get a link.

## Put it on GitHub + Netlify (updates automatically)
1. On GitHub make a new repository (for example `my-training`).
2. Click **Add file → Upload files**, drag in everything from this folder, then **Commit changes**.
3. On Netlify: **Add new site → Import an existing project → GitHub** → pick the repo.
4. Build command: leave empty. Publish directory: `.`  → **Deploy**.
5. To update later, upload the new `index.html` to GitHub — Netlify updates the site by itself.

## Put it on your phone like an app
Open your Netlify link in Chrome → **⋮ → Add to Home screen / Install app**.
It opens full screen and works without internet.

## Moving your progress
Progress is saved in the phone's browser. To move it (for example from the old file to the website):
Progress tab → **Copy backup**, then on the new one → **Restore** and paste.

## Files
- `index.html` — the whole app
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` — app name and icon
- `sw.js` — lets it work offline
- `netlify.toml` — Netlify settings
