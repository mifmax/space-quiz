# Space Quiz

Space Quiz is a self-contained browser quiz about space. It includes standard and timed challenge modes, immediate answer feedback, shareable results, and a responsive light/dark interface.

## Run locally

No build step or server is required. Open `index.html` directly in a browser, or serve the repository with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

The site is deployed to GitHub Pages by the workflow in `.github/workflows/pages.yml` whenever changes are pushed to `main`. Pull requests run the workflow's validation job without deploying.
