# Meridia — Luxury Real Estate HTML Template

A five-page HTML template for private real estate advisories and luxury
brokerages. Cinematic full-bleed hero, navy-and-brass palette, Cormorant
Garamond display serif paired with Inter.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home — cinematic hero, featured listings, stats band, two-column editorial, testimonial, closing CTA |
| `listings.html` | Active portfolio — filter bar, 9-listing grid, pagination |
| `property.html` | Single property page — gallery, specs, features list, sticky agent card with inquiry form |
| `about.html` | Firm story, 4-partner team grid, testimonial, CTA |
| `contact.html` | Three offices, phone line, full inquiry form |

## Quick start

Open `index.html` in a browser. No build step.

## Replace images

All visuals under `assets/img/` are labeled SVG placeholders. Each `<img>` is
preceded by a comment with recommended dimensions:

| File | Where | Recommended |
|---|---|---|
| `hero.svg` | Home cinematic hero | 2400×1600 — architectural exterior at dusk |
| `listing-1.svg` → `listing-6.svg` | Listings strip / grid / property gallery | 1000×750 |
| `about.svg` | About page two-column image | 900×1125 |
| `team-1.svg` → `team-4.svg` | Team portraits (about page) | 600×800 |

## Design tokens

Change palette in `assets/css/styles.css`:

```css
:root {
  --bg: #f5f3ee;
  --ink: #1a2139;
  --brass: #b59553;
  /* ... */
}
```

## Tech

Vanilla HTML + CSS + JS. Google Fonts via preconnect. Responsive 320 / 768 /
1024 / 1440+. Semantic landmarks, keyboard focus, reduced-motion support.

## License

Free for personal and commercial use. See html.design license page.
