# harshapakki.github.io

Personal portfolio site, served at <https://harshapakki.github.io/>.

A single self-contained `index.html`: no build step, no dependencies to install.
Three.js is loaded from a CDN for the hero scene, everything else (styles, the
control-loop demo, the skills panel) is inline.

## Editing

Open `index.html` and edit in place. The content lives in three places:

- the markup, for the hero, the SDE and FDE cards, and the work history
- the `skills` array in the script, for the skills panel and its proof points
- the `projects` array, for the project cards

Push to `main` and GitHub Pages redeploys.

## Notes

- Light and dark themes are both defined as CSS tokens, with a manual toggle
  that persists in `localStorage`
- Respects `prefers-reduced-motion` by holding the 3D scene still
- No analytics, no trackers, no cookies
