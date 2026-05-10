# Andrew & Tamlyn — Belfast Party Guide

A single-page static site for our Belfast party on **Saturday 5 September 2026**.

## Files

- `index.html` — all content
- `styles.css` — styling
- `CNAME` — custom domain for GitHub Pages (add when domain is purchased)

## Local preview

It's plain HTML/CSS — open `index.html` directly in a browser, or serve the
folder with any static server, e.g.:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy (GitHub Pages)

1. In the repo settings → **Pages**, set the source to the `main` branch, root.
2. Once a custom domain is purchased, add a `CNAME` file containing the
   domain (e.g. `belfast.example.com`) and configure the DNS record with
   the registrar.
