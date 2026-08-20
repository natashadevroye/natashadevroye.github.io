# Natasha Devroye academic homepage

This is a lightweight static site for GitHub Pages, 
using content from <https://devroye.lab.uic.edu/>.

## Files

- `index.html` contains the page content.
- `publications.html` contains the publications list.
- `teaching.html` contains teaching history and teaching evaluation links.
- `cv.html`, `news.html`, and `people.html` contain the remaining site tabs.
- `styles.css` contains the visual styling.
- `.nojekyll` tells GitHub Pages to serve the files exactly as written.

## Publish on GitHub Pages

1. Create a repository named `USERNAME.github.io`, replacing `USERNAME` with
   your GitHub username.
2. Add these files to the repository and push to the `main` branch.
3. In the repository settings, open **Pages**.
4. Choose **Deploy from a branch**, then select `main` and `/root`.
5. Your site will appear at `https://USERNAME.github.io/`.

For a project repository instead of a user homepage, publish these files from
the `main` branch and the site will be served from
`https://USERNAME.github.io/REPOSITORY/`.

## Content notes

The portrait currently loads from a UIC-hosted website. For a fully
self-contained GitHub repository, save a local copy later as `portrait.png` and
change the `img` source in `index.html` to `portrait.png`.
