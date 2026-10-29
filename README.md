# Yedu & Greeshma — Wedding Invitation (groom-side)

Plain HTML5 / CSS3 / vanilla JavaScript. No build step — deploy the folder to any static host
(GitHub Pages, Netlify, Vercel, S3, shared hosting).

## Run locally
    python3 -m http.server 8080      # then open http://localhost:8080

## Things to do before going live
1. **Photos** — drop files into `assets/images/gallery/`:
   `groom.jpg`, `bride.jpg` (portraits, 3:4) and `photo-01.jpg` … `photo-06.jpg` (gallery).
   Until then, labelled placeholders are shown automatically.
2. **Share links** — in `index.html` replace `https://YOUR-DOMAIN/` (og:url, og:image, twitter:image)
   with the real site address. Image is `assets/images/share/og-thumbnail.jpg` (1200×630).
3. **Maps buttons** — currently Google Maps *search* links for the two venue names. Replace with the
   venues' own "Share" links from Google Maps once confirmed.
4. **Music** — `assets/audio/inkem-inkem_g300U6Yp.mp3` is carried over from the template.
   Replace with a track you are licensed to use (keep the same filename or update `index.html`).

## Key files
| Role | Path |
|------|------|
| Opening video | `assets/video/invitation-reveal.mp4` |
| Cover / hero | `assets/images/cover/cover.png`, `assets/images/hero/` |
| Countdown target | `js/main.js` → 2026-12-30 10:30 IST (`+05:30`, correct in any time zone) |
