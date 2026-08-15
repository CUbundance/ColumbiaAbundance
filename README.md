# Columbia Abundance

Simple site for the Columbia University Abundance chapter. Plain HTML/CSS/JS —
no build tools, no `npm install`, nothing to set up. Just edit the files
directly.

## Viewing the site

Open `index.html` in your browser (double-click it, or drag it into a browser
window). That's it — no server required.

## Files

- `index.html`, `about.html`, `contact.html` — the three pages
- `css/styles.css` — all styling. Colors, fonts, and spacing are defined as
  variables at the top of the file (`:root { ... }`) — change those to
  re-theme the whole site at once.
- `js/nav.js` — small script for the mobile menu toggle, nothing else.
- `assets/` — empty for now; drop a logo or images here later.

## Two things to fill in

1. **Mission statement** — `about.html` (and a short teaser on `index.html`)
   has a placeholder box marked `TODO: replace with chapter mission
   statement`. Replace it with your own text.
2. **Sign-up link** — `contact.html` has a "Open sign-up form" button that
   currently points to `#`. Once you have a Google Form, replace the `href="#"`
   on that button with your form's URL.

## Publishing it later

Not needed yet, but when you're ready: GitHub Pages or Vercel can both host a
static site like this for free, straight from this folder.
