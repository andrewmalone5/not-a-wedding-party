# A&T Favicon Pack

Drop the contents of this folder at the root of your site (e.g. `/public/` or repo root for GitHub Pages).

## Files

| File | Purpose |
|---|---|
| `favicon.svg` | Primary favicon. Vector, fonts embedded as base64 — no external requests. |
| `favicon-16x16.png` | Browser tab fallback (small). |
| `favicon-32x32.png` | Browser tab fallback (standard). |
| `favicon-48x48.png` | Windows + bookmarks. |
| `favicon-96x96.png` | Higher-density browser tabs. |
| `apple-touch-icon.png` | 180×180 — iOS home-screen icon. |
| `android-chrome-192x192.png` | Android home-screen / PWA. |
| `android-chrome-512x512.png` | Android splash / PWA / Open Graph fallback. |
| `site.webmanifest` | PWA manifest referencing the Android icons. |

## HTML — paste into `<head>`

```html
<link rel="icon" type="image/svg+xml" href="/favicon.svg">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="theme-color" content="#D85A4D">
```

## Type & color

- **A · T** — Cormorant Infant, weight 600
- **&** — Cormorant Garamond Italic, weight 500, sized 0.78em, baseline raised 0.04em
- **Coral** `#D85A4D`  ·  **Cream** `#F2E9DC`  ·  **Ink** `#2c2522`
