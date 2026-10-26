# Jeremy Miller Audio

Source for www.jeremymilleraudio.com. A plain static site: no build step.

- `index.html` is the whole page (styles and scripts are inside it).
- `gallery/` holds the photos, `favicon.svg` is the browser icon.
- Publishing: Cloudflare Pages deploys this repository automatically whenever the `main` branch changes.
  Use framework preset "None", build command empty, output directory `/`.
