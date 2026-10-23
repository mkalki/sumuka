# Sumuka Steels website

This is a static website built with plain HTML, CSS, and JavaScript. It has no build step or server-side runtime, so the project can be deployed directly from its root directory to static hosting such as GitHub Pages, Netlify, or Vercel.

## Local preview

Open `index.html` in a browser, or serve the project directory with any static file server. For example, with Python installed:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Connect the repository to a static host and set the publish/output directory to the project root. No install, build, or environment variables are required. Keep `index.html`, `about.html`, `404.html`, `styles.css`, `script.js`, and `favicon.svg` together in the published directory.
