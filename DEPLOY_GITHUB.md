# Building A only — GitHub Pages

This package contains only the four original Building A GLB files (Floor, Interior, Roof, Walls). Building B and Landscape files and loader entries are removed.

Upload **the contents of this folder** to the root of the `garden-blocks-3d` repository, including `.github/workflows/deploy.yml` and `vite.config.js`. GitHub Pages Settings > Pages > Source: GitHub Actions. The site URL after deployment is https://christabellevina.github.io/garden-blocks-3d/ .

**Important:** Delete the old Building B and Landscape files from the repository if they are still there. Uploading this ZIP's contents does not automatically delete old files on GitHub. The app will not request them.

The four GLB files are unchanged. The source GLB files' internal geometry is not altered. Model rendering and interactive controls still require browser testing. The build and deployment require a successful GitHub Actions run.
