# Travel With Fadi.pk

One-page website for Travel With Fadi.pk: guided tours to Hunza, Skardu, Swat, Naran Kaghan and Murree, with booking through WhatsApp.

## What's here

- `index.html`: the whole site (HTML, CSS and JS in one file), including the Film Room page at `#films`
- `videos/`: trip clips, compressed for the web, each with a poster `.jpg`
- `images/`: the site's own photos

## Run it

Open `index.html` in a browser, or serve the folder with any static host (Cloudflare Pages, Netlify, GitHub Pages). There's no build step.

## Adding a video

1. Compress it and put it in `videos/` with a short name (for example `hunza-lake.mp4`), plus a poster frame `hunza-lake.jpg`.
2. Add a line to the `clips` list near the end of `index.html`: `['hunza-lake','Caption','high','One-line note']`. The chapter is `high`, `dark` or `road`.
