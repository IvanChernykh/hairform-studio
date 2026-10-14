# FORM / Hair Studio

Minimal monochrome Three.js hairstyle planner. Drag the model to rotate; use the bottom timeline to explore growth; click the top controls for haircut, styling, and care notes.

## GitHub Pages
The GitHub Actions workflow in `.github/workflows/pages.yml` deploys the repository root on every push to the default branch. In repository Settings → Pages, set Build and deployment source to **GitHub Actions** if it is not automatically selected. Once the workflow succeeds, the site is available at https://ivanchernykh.github.io/hairform-studio/.

The head is a procedural visual approximation, not a photogrammetry scan. Three.js is loaded from jsDelivr, so the page requires network access.
