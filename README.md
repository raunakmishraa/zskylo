# Zskylo website

Astro + TypeScript marketing website for Zskylo.

## Development

- Node.js 20.3.0 or newer
- `npm install`
- `npm run dev`
- `npm run check`
- `npm run build`

## Pages

- `/` — Home
- `/services/` — all three divisions: Software Development, Brand Growth and Our Products
- `/work/` — six approved software projects with visual editorial project covers
- `/products/` — AashrayaCare, Yittzy and Cashify Wallet
- `/about/` — brand overview and contact details
- `/contact/` — direct email and phone contact
- `/privacy/`, `/terms/`, `/refund/`, `/cookies/` — public-facing policy pages

## Content safeguards

- Brand Growth portfolio is intentionally marked Coming Soon.
- Yittzy is marked Coming Soon.
- Project artwork is a designed visual overview, not a screenshot or claim about the live website's interface.
- No testimonials, metrics, client outcomes, certifications or business-registration claims have been invented.
- The site does not include analytics or advertising trackers.
- Legal policy revision dates and internal review notes belong in `docs/legal/*.md`, not in the frontend.
- Zskylo is described as a public-facing brand, not as a separately registered legal entity.

## Brand system

Uses the brand-book palette: Chalk White `#F7F5F0`, Navy Ink `#2D3A52`, Dark Navy Ink `#1D2B42`, and Baltic Blue `#3B5998`. Manrope is the primary typeface. The supplied Zskylo SVG is used for the site logo and favicon.

## Before production deployment

1. Run `npm install`, `npm run check` and `npm run build`.
2. Review the legal pages and confirm the contracting party and any applicable service terms.
3. Consider self-hosting Manrope if third-party font requests are not desired.
4. Test all pages at mobile, tablet and desktop widths, and verify all external project URLs.
