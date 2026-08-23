# Marian Stories

A self-contained static page published with GitHub Pages.

## Development

Edit `src/index.html`, then build the deployable page:

```sh
npm run build
```

## Deployment

Publish `dist/index.html` to the `gh-pages` branch:

```sh
npm run deploy
```

In the GitHub repository settings, set **Pages → Build and deployment → Source**
to **Deploy from a branch**, then select the `gh-pages` branch and `/ (root)`.
