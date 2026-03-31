# Portfolio Builder

A browser-based portfolio generator: pick a template, fill in your details, and export a static site you can host anywhere—including [Netlify](https://www.netlify.com/) with the in-app deploy guide.

**Live:** open [`index.html`](index.html) in a browser, or serve the folder with any static file server.

## Features

- **Five templates:** Minimal Elegance, Creative Fusion, Dev Terminal, Project Manager, Product Manager
- **Guided steps:** template → customize (bio, projects, skills, contact, optional photo) → preview → export
- **Static output:** download a self-contained site; no build step required
- **Deploy help:** Netlify-oriented instructions built into the UI

## Run locally

From this directory:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. (A plain `file://` open also works for many features; a local server avoids browser restrictions for some operations.)

## Repository layout

| File        | Purpose                          |
|------------|-----------------------------------|
| `index.html` | Single-page app (HTML, CSS, JS) |
| `LICENSE`  | MIT License                       |

## License

MIT — see [LICENSE](LICENSE).

© 2026 Mohammed Ilyas Ahmed
