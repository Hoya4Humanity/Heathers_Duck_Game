# Heather’s Duck Game 🪠🦆

A tiny, dependency-free browser game. BONK ducks, BOINK bosses, and beat the timer.

## Play locally
Option A: open `index.html` directly.

Option B: run a simple server:
- `python -m http.server 8080`
- open `http://localhost:8080`

## Controls
- Click/tap: 🪠 BONK (normal hit)
- Double-click / double-tap: 🧻 BOINK (TP Roll special, cooldown)
- Space: pause/resume
- R: reset run
- M: mute/unmute

## Boss Levels
Every 3 levels (3, 6, 9, ...) is a boss fight.
The boss has multiple HP and uses telegraph → charge → stun loops.
Defeat it before the timer hits 0.

## Deploy (GitHub Pages)
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select branch: `main`
5. Select folder: `/ (root)`
6. Save. Your site publishes to:
   `https://hoya4humanity.github.io/Heathers_Duck_Game/`

### Troubleshooting
- The playable URL is your GitHub Pages site (`https://hoya4humanity.github.io/Heathers_Duck_Game/`), not a `github.com` file/blob page.
- If you see a README instead of the game, verify Pages is deploying from `main` + `/ (root)` and that `index.html` is at the repository root.

## Notes
- No external assets, no build tooling.
- All logic lives in `index.html`.
