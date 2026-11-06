# ScamShield

Educational website about common scam types. Pure HTML and CSS, no JavaScript.

## Files
- `index.html` Home
- `scam-types.html` Scam Types (8 scams, comparison table, example messages)
- `stay-safe.html` Stay Safe (red flags, checklist, steps if scammed, where to report, FAQ)
- `404.html` custom error page (works when hosted at the site root)
- `style.css` all styling (dark mode, mobile menu, print styles)
- `video/` local explainer video (mp4 + webm), poster and captions
- `images/` SVG illustrations, `og-image.png` share preview

## Run
Open `index.html` in a browser, or host the folder on any static host (Vercel, Netlify, GitHub Pages).

## Notes
- Replace `video/explainer.mp4` and `explainer.webm` with your own video if you wish.
- The mobile menu uses a CSS checkbox, so it works without JavaScript.
- `404.html` uses root-relative links (`/style.css`), so it works on a host root, not when opened from disk.
