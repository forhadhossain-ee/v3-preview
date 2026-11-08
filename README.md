# v3-redesign preview

This repository hosts the redesigned portfolio (v3) at its own GitHub Pages URL:
https://forhadhossain-ee.github.io/v3-preview/

The live site lives in a separate repository and is never affected by changes here. This preview intentionally sends `noindex` directives and must not be submitted for indexing before production launch. Images and the CV currently load from the live domain's public asset paths.

## Files
- `index.html` — homepage
- `projects.html` — project archive
- `css/style.css`, `js/script.js` — design system
- `.nojekyll` — required for GitHub Pages to serve this folder

## Deploy
Every push to `main` deploys automatically via GitHub Actions.

Preview URL: https://forhadhossain-ee.github.io/v3-preview/