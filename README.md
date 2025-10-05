# White Water Rafting (WWR) — WDD130

Validator-friendly static site ready for GitHub Pages.

## Structure
- index.html — Home (Hero, newsletter, CTA, grid content)
- about.html — About the company
- trips.html — Trips (3 cards + summary table + CTA to contact)
- contact.html — Contact info, team, accessible form with radios & checkbox
- thankyou.html — Confirmation page
- rafting.css — Single CSS file
- images/ — Lightweight SVG placeholders

## Deployment (GitHub Pages)
1. Create a repository (e.g., `wdd130`).
2. Place this folder as `wdd130/wwr/`.
3. Commit & push.
4. Enable Pages: Settings → Pages → Source: `main` → `/root` (or `/docs`).
5. Live URL: `https://<your-username>.github.io/wdd130/wwr/`

## Validators
- HTML: https://validator.w3.org/nu/
- CSS: https://jigsaw.w3.org/css-validator/

> Replace `images/map-placeholder.svg` with a Google Maps `<iframe>` for production.
> Remove inline style attributes Google adds to the iframe; style via CSS instead.
