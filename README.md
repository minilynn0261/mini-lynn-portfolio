# Mini Lynn Portfolio

Portfolio website for Mini Lynn, web developer. It's a single static page, so it needs no build step.

## Files

- `index.html`: the whole site (styles and scripts included)
- `logo.svg`: the logo, also used as the browser tab icon
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `mini-lynn-portfolio`.
2. Upload all the files in this folder to the repository root (Add file > Upload files). Include `.nojekyll`.
3. Go to Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", pick `main` and `/ (root)`, then Save.
5. After a minute or two the site is live at `https://<your-username>.github.io/mini-lynn-portfolio/`.

To use your own domain, add it under Settings > Pages > Custom domain.
