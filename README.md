# anastasiiasenyk.com

Personal landing page. Static HTML + CSS, no build step.

Served by GitHub Pages from the `main` branch root, on the custom
domain `anastasiiasenyk.com` (see `CNAME`).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole page. Styles are inline in a `<style>` block. |
| `photo.jpg` | 1440×959, EXIF stripped, progressive JPEG. |
| `CNAME` | Tells GitHub Pages which custom domain to serve. Do not delete. |
| `.nojekyll` | Skips Jekyll processing. |

## Editing

Edit `index.html` and push to `main`. GitHub Pages redeploys in about a minute.

To preview locally:

    python3 -m http.server 8000

then open http://localhost:8000
