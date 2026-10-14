# SportynX RYSE — onboarding prototype

Live (GitHub Pages, auto-deploys on every push to `main`):
https://sportynx.github.io/sportynx-ryse-prototype-/

## Workflow — do this after EVERY change, without being asked
1. Edit `src/prototype.html` (the single source of truth; same file as the Claude artifact "RYSE Launch Screen").
2. Run `python3 build.py` to regenerate `index.html` (adds the fullscreen iPhone web-app head).
3. Commit and push to `main`. GitHub Pages redeploys automatically in ~1 minute.
4. If working in a Claude session that also has the artifact, republish the artifact from the same source.

Never ask the user to do manual deploy steps.

## Viewing on iPhone
Open the link in Safari → Share → Add to Home Screen → launch "RYSE" (fullscreen, edge to edge).
