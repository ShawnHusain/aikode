# aikode

Website for [Aikode](https://aikode.ca), a small Canadian software studio.

A single static page — plain HTML, CSS and a little JavaScript. No build step or dependencies.

## Structure

```
index.html        Page content and metadata
css/styles.css    Styles and colour tokens
js/main.js        Mobile menu, scroll fade-ins, footer year
assets/           Logo and favicon
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

then visit http://localhost:8000.

## Deploying

Any static host works (GitHub Pages, Netlify, Cloudflare Pages, Azure Static Web Apps). Publish the repository root as-is.
