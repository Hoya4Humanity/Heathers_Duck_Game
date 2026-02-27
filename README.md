# Heather’s Duck Game 🪠🦆

A tiny, dependency-free browser game. Click/tap ducks in the lake with a toilet plunger. Clear the level to advance. Each level adds more ducks and speed.

## Play locally
Option A: open `index.html` directly.

Option B: run a simple server:
- `python -m http.server 8080`
- open `http://localhost:8080`

## Controls
- Click/tap: plunger a duck
- Space: pause/resume
- R: reset
- M: mute/unmute
- On-screen: reset + sound toggle

## Deploy (GitHub Pages)
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch: `main`
5. Select folder: `/ (root)`
6. Save. Your site will publish to:
   `https://<username>.github.io/Heathers-Duck-Game/`

## Notes
- No external assets, no build tooling.
- All logic lives in `index.html`.
