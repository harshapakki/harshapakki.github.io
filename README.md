# harshapakki.github.io

Personal portfolio site, served at <https://harshapakki.github.io/>.

A single self-contained `index.html`: no build step, no dependencies to install,
no external scripts. Fonts come from Google Fonts; everything else is inline.

## Editing

Open `index.html` and edit in place. Most content lives in plain markup; the
interactive parts are driven by small data arrays in the script:

- `tiers` for the system design architecture explorer
- `hops` for the network trace (noVNC → nginx → websockify → VNC → firewall)
- `stages` for the deployment pipeline demo
- `skills` for the skills panel and its proof points
- the project and research card arrays

Push to `main` and GitHub Pages redeploys.

## Notes

- Light and dark themes are both defined as CSS tokens, with a manual toggle that persists in `localStorage`
- Respects `prefers-reduced-motion`: demos render their final state instead of animating
- No analytics, no trackers, no cookies
- The previous engineering page is parked in `_engineering/` and is not linked from the site
