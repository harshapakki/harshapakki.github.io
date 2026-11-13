# harshapakki.github.io

Personal portfolio site, served at <https://harshapakki.github.io/>.

A single self-contained `index.html`: no build step, no dependencies to install,
no external scripts. Fonts come from Google Fonts; everything else is inline.

## Editing

Open `index.html` and edit in place. The page is five sheets: case studies,
platform, system design, experience and contact. Most content is plain markup;
the interactive figures are driven by small data arrays in the script:

- `screen`, `json`, `convo` for the legacy → API → agent loop (Fig. 1)
- `stages` for the deploy pipeline (Fig. 2)
- `rungs` for the escalation ladder (Fig. 4)
- `hops` for the network trace (Fig. 6)
- `tiers` for the system design explorer

Push to `main` and GitHub Pages redeploys.

## Notes

- Two themes, drafting paper (light) and blueprint (dark), defined as CSS tokens with a toggle that persists in `localStorage`
- Respects `prefers-reduced-motion`: demos step through without typing effects
- No analytics, no trackers, no cookies
- The previous engineering page is parked in `_engineering/` and is not linked from the site
