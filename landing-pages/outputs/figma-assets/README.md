# Figma assets

Pulled from the Growisto Review File via the Figma REST API.

- `assets/` — the 46 named images wired into the `*-images.html` prototypes (4.3 MB)
- `world-map.svg` — both map variants in one file. Every dot was rewritten from a
  4-arc bezier path to a `<circle>` and the fill set to `currentColor`, taking it
  from 728 KB to 128 KB (15 KB gzipped). Colour it from CSS.
- `icon-*.svg`, `logo-*.svg` — single-colour icons use `currentColor`; multi-colour
  marks (Amazon, Shopify, the Growisto mark) keep their own palette.

Not included in git (see .gitignore): `img/` (raw fills, named by imageRef) and
`unused/` (121 fills belonging to other artboards in the same Figma file).

## Excluded on purpose

`hubble` and `Unilever` logos are present in the Figma file but appear on neither
permission-cleared list in `landing-pages/CLAUDE.md`. They were downloaded but are
not wired into any page.

## Known placeholders

The portraits (`case-portrait-a`, `case-photo-b`, `case-avatar-c`,
`testimonial-portrait`) are stock/AI images from the design file, not photographs
of the people the quotes are attributed to. Replace before any client sees these.
