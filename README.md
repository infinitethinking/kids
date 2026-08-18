# kids

Planning hebdomadaire des entraînements (triathlon, BMX, athlétisme) pour O & L.

Published site: https://infinitethinking.github.io/kids/

`index.html` is a single self-contained page (all CSS and JavaScript inline, no
external assets), so it also works by opening the file directly in a browser.

## How it is published

`.github/workflows/pages.yml` publishes the repository root to GitHub Pages on
every push to `main`. The workflow enables Pages itself on its first successful
run, so no change in **Settings → Pages** is needed.

If the first run fails because Actions cannot enable Pages, set it manually:
**Settings → Pages → Build and deployment → Source: GitHub Actions**, then
re-run the workflow.

Note: `planning_entrainements.html` is currently an identical copy of
`index.html` and is served at
https://infinitethinking.github.io/kids/planning_entrainements.html.
