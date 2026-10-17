# glyph-site

Public static site for **glyph.kodahtech.com**: marketing page, privacy policy, terms, support.
Served by GitHub Pages from `main` (root). The app itself lives in the private `glyph` repo.

- Tokens in `styles.css` mirror `src/theme/index.ts` in the app; change them together.
- `CNAME` pins the custom domain; DNS is a CNAME `glyph -> dylan-kodahtech.github.io` at GoDaddy.
- No build step. Edit HTML, push, live in about a minute.
