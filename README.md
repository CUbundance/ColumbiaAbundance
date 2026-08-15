# Columbia Abundance

Simple site for the Columbia University Abundance chapter. Plain HTML/CSS/JS —
no build tools, no `npm install`, nothing to set up. Just edit the files
directly.

## Viewing the site

Open `index.html` in your browser (double-click it, or drag it into a browser
window). That's it — no server required.

## Files

- `index.html`, `about.html`, `leadership.html`, `contact.html` — the site's pages
- `css/styles.css` — all styling. Colors, fonts, and spacing are defined as
  variables at the top of the file (`:root { ... }`) — change those to
  re-theme the whole site at once.
- `js/nav.js` — small script for the mobile menu toggle, nothing else.
- `assets/` — empty for now; drop a logo or images here later.

## Things to fill in

1. **Mission statement** — `about.html` (and a short teaser on `index.html`)
   has a placeholder box marked `TODO: replace with chapter mission
   statement`. Replace it with your own text.
2. **Sign-up link** — `contact.html` has a "Open sign-up form" button that
   currently points to `#`. Once you have a Google Form, replace the `href="#"`
   on that button with your form's URL.
3. **Substack link** — every page's footer has a "Substack" link that also
   currently points to `#`, marked with a `TODO` comment. Replace it with your
   Substack URL once you have one.
4. **Leadership Team bios** — `leadership.html` lists the 4 team members (name
   + class year, no titles), each with a placeholder bio line still marked
   `[One line about this person.]`. Fill those in if you want them, or delete
   the `<p class="officer-bio">` line for anyone who doesn't need one. To add
   another person, copy/paste an `.officer-card` block; the circle shows their
   initial, or swap it for a photo later with an `<img>` inside
   `.officer-avatar`.

## Publishing it later

Not needed yet, but when you're ready: GitHub Pages or Vercel can both host a
static site like this for free, straight from this folder.
