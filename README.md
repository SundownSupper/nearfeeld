# NEARFEELD

Scent you carry. Minimal printed carriers for your own perfume: C-01 card, V-01 car vent, S-01 shoe pod.

Live site: https://sundownsupper.github.io/nearfeeld/
Instagram: [@nearfeeld](https://www.instagram.com/nearfeeld/)

## Files

| File | What it is |
|---|---|
| `index.html` | The website |
| `404.html` | "Signal lost" page for broken links |
| `favicon.svg` | Browser tab icon |
| `apple-touch-icon.png` | iPhone home-screen icon |
| `og-image.jpg` | Preview image when the link is shared |
| `assets/img/` | Product renders (transparent WebP) made from the C-01 / V-01 / S-01 models |
| `assets/film/` | The three 15 s product films (web size, no audio) + poster frames |
| `nearfeeld-teaser.mp4` | Original brand teaser (not used on the page) |
| `brand/` | Logo files |
| `BRAND.md` | Brand guide: colors, fonts, voice, IG templates |

## Editing links

Open `index.html` and find the `LINKS` block near the top. Change only the text inside the quotes.

## Updating product images

The renders come from `~/nearfeeld/web-renders/` (not in this repo): `studio.js` holds one entry per shot
in `SHOTS`, `shoot.py` renders them to `out/`, then convert to WebP into `assets/img/`.
