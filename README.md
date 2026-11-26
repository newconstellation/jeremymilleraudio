# Jeremy Miller Audio

Source for www.jeremymilleraudio.com. A plain static site: no build step.

- `index.html` is the whole page (styles and scripts are inside it).
- `photos/` holds the large portrait and section photos; `gallery/` holds the gallery photos; `hero.jpg`, `hero-sm.jpg` and `share.jpg` are the top image and the link-preview image.
- `robots.txt` and `sitemap.xml` are for search engines.
- Publishing: Cloudflare deploys this repository automatically whenever the `main` branch changes.
  Framework preset "None", build command empty, output directory `/`.
