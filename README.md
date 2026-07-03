# bookalive

The **Books Alive** project site — a library of living books (small paper
creatures passed hand to hand at conventions), designed by **Ryan Cross**.

Served via GitHub Pages at **[booksalive.xyz](https://booksalive.xyz)** (custom
domain set in `CNAME`; Pages source = `main` branch, `/` root).

## Files
- `index.html` — the page (self-contained markup + inline SVG motifs).
- `style.css` — styles, brand palette, and `@font-face` (local fonts).
- `fonts/` — Cormorant + EB Garamond as `woff2` (SIL OFL 1.1; see `*-OFL.txt`).
- `favicon.svg` — compass-star mark.
- `CNAME`, `.nojekyll` — GitHub Pages config (do not remove).

## Design
Black-on-cream in Ryan's brand palette (cream `#F4E6CD`, navy `#16283F`, gold
`#C6902E`, sage, mauve), with celestial/geometric motifs drawn from the book
covers: a framed hero, radiant compass star, moon phases, sparkles, leaf
sprigs, and an open book with a rising sun.

## Email capture (one step to activate)
The signup form is wired but **not yet capturing** — it needs an endpoint:
1. Create a free form at [formspree.io](https://formspree.io) (or another
   provider) and copy its POST endpoint.
2. In `index.html`, set `var ENDPOINT = "..."` in the inline script to that URL.
3. Commit & push. Submissions will then be captured; the on-page thank-you
   message stays the same. Until then the form shows the thank-you without
   storing anything.

No booklet PDFs are hosted here — the books are described in text only.
