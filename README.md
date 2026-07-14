# Sibongile Pradhan — website

Marketing site for Sibongile Pradhan, a practitioner offering mediation,
coaching, deep listening, facilitation, training and grief tending, grounded
in Nonviolent Communication (NVC). Based in Edinburgh.

**Live:** https://alicia-stem.github.io/sibongile_website/

## Structure

- **`index.html`** — single long-scrolling homepage with four sections:
  Home, Services ("Areas of Work" — the five elements), About, Contact.
- **`booking.html`** — "Book a free session" page. The form opens a pre-filled
  email to Sibongile; the focus dropdown auto-selects from a `?focus=` query
  param passed by each service's booking button.
- **`assets/`** — images used by the site: the wordmark logo and the portrait.
- **`design/`** — source material, not served: the original design exports
  (`homepage.*`, `areas_section.*`) and the editable logo source
  (`logo-wordmark-source.png`, checkerboard background baked in).
- **`text`** — the real copy provided by Sibongile, used as the content source.

## Tech

Static HTML, no build step. Styling via the Tailwind CSS CDN with a small
custom theme (colours, fonts, type scale) configured inline in each page's
`<head>`. Fonts: Source Serif 4 (headings) and Manrope (body).

## Run locally

```bash
python3 -m http.server 8722
# then open http://localhost:8722/
```

## Deployment

Hosted on GitHub Pages from the `main` branch (root). Pushing to `main`
updates the live site within a minute or so.

## Notes

- The logo is a transparent PNG derived from `design/logo-wordmark-source.png`
  with the checkerboard background removed.
- Client testimonials are quoted verbatim from `text`.
