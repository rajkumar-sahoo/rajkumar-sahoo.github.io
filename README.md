# rajkumarsahoo.github.io

Personal academic site for Dr Rajkumar Sahoo, Max Weber Fellow, School of Transnational
Governance, European University Institute, Florence.

Live at <https://rajkumarsahoo.github.io>

## Layout

- `index.html` — the entire site. Single self-contained file: no build step, no dependencies,
  no framework. Fonts come from Google Fonts; everything else is inline.
- `.nojekyll` — tells GitHub Pages to serve the files as-is rather than running them through
  Jekyll.

## Editing

Open `index.html`, change the text, save, then:

```bash
git add -A && git commit -m "update" && git push
```

Pages redeploys within a minute or two.

The content sections are, in order: lede, About, Research (thematic threads), Papers &
projects (catalogue with status chips), Talks & convenings, Teaching, Contact. Status chips
use three classes: `status` (neutral), `status is-active` (in progress), `status is-accepted`
(accepted/confirmed).

## Design

Colour, type, and spacing are all driven by CSS custom properties in the `:root` block at the
top of `index.html`. Light and dark palettes are defined separately; the dark palette is
repeated once for `prefers-color-scheme` and once for an explicit `data-theme="dark"`, so
edit both if you change a colour.

Typefaces: Bricolage Grotesque (headings), Newsreader (body), IBM Plex Mono (labels and
metadata).

## Still to add

- Publications list (nothing is currently listed as published)
- Education block — PhD institution and year, MPhil
- ORCID
- Headshot
