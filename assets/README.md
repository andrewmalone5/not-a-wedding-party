# Site assets

Save the photos for the "story" section here, with these exact filenames:

- `causeway-coast.jpg` — wide landscape shot of Andrew & Tamlyn on the rock above the sea
- `donuts.jpg` — close-up selfie eating sugar-coated donuts
- `picnic.jpg` — overhead selfie on the floral picnic blanket

The HTML in `index.html` references those paths directly. Drop the files in,
commit, and push.

## Sizing tips

The browser will scale them, but for fast loads:

- **Hero (causeway-coast):** ~1600px wide, JPEG quality 80, ~250–400 KB target
- **Pair (donuts, picnic):** ~1000px wide each, JPEG quality 80, ~150–250 KB

If you have ImageMagick:

```sh
magick original.jpg -resize 1600x -quality 80 causeway-coast.jpg
magick original.jpg -resize 1000x -quality 80 donuts.jpg
```
