# Policy Oracle

Static website for Policy Oracle Limited. Plain HTML, CSS, and JavaScript with no build step.

## Deploy to GitHub Pages
1. Push this folder to a GitHub repository (everything at the repo root).
2. In the repo: Settings > Pages.
3. Source: Deploy from a branch. Branch: main. Folder: / (root). Save.
4. Wait a minute, then open the URL GitHub shows.

## Preview locally
- Double-click index.html, or
- Run a local server: node server.js, then open http://localhost:3000

## Important: file names are case sensitive on GitHub
GitHub Pages runs on Linux, which treats css and CSS as different folders.
The names here must stay exactly as they are: css, js, styles.css, pages.js,
animations.js, app.js, courses.js. If you rename anything, match the case in index.html.

## Regenerating the course catalogue
courses.js is generated. To rebuild it, run from the repo root:
  node tools/generate_600.js
