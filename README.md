# hollierichmond.com

Portfolio site for Hollie Richmond — a single static page, no build step.

## Structure

- `index.html` — the whole site: markup, styles and scripts in one file
- `img/w01–w11.jpg` — project plates shown on the page (1500px wide)
- `img/full/w01–w11.jpg` — high-resolution versions loaded only when a plate is expanded (2600px wide)
- `CNAME` — the custom domain GitHub Pages serves this from
- `favicon.svg`

## Editing

Open `index.html` and edit directly. Each project is one `<article class="proj">` block
containing a `.rail` (number, client, title, spec list) and a `.plate` button holding the image.
To add a project, copy a block, bump the number, and drop the two image sizes into `img/` and `img/full/`.

## Publishing

Commit and push to `main`. GitHub Pages redeploys automatically.
