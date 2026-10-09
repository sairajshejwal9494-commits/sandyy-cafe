# Sandyy Cafe

A responsive restaurant website for Sandyy Cafe, featuring the menu, rupee prices, location directions, and mobile navigation.

## Live website

[Visit Sandyy Cafe](https://sairajshejwal9494-commits.github.io/sandyy-cafe/)

## Run locally

```sh
npm install
npm start
```

Open the address printed by the server. The default port is `3000`; set `PORT` in a local `.env` file to use another port. `.env` is excluded from Git.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the static site from `public/` whenever changes are pushed to `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**. Once the workflow completes, GitHub Pages will show the public website URL in the repository's Pages settings.

The Express server in `server.js` is for local use; GitHub Pages hosts the static website and does not run the Express API.

## Cafe location

[Open Sandyy Cafe in Google Maps](https://maps.app.goo.gl/T35AsEo2VEbRprYP7?g_st=ic)
