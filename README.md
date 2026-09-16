# MediaBay Fashion Master Theme V2 — Editorial Store

A premium, non-ecommerce fashion-store theme designed as a digital brand experience rather than a product catalogue.

## Design idea
- No product grid
- No shopping cart
- No generic stock photography
- Oversized real store logo as the visual hero
- Brand Atlas using real brand marks via Simple Icons CDN, with text fallback
- Editorial sections for philosophy, worlds, story and reputation
- Physical-store CTA as the conversion goal
- Mobile-first responsive layout
- Subtle reveal motion and scroll progress

## Data model
Edit `content.json` to create a new client site. Brand records use:
- `name`
- `slug` (Simple Icons slug)
- `url`

The theme is reusable for fashion boutiques, footwear, accessories and lifestyle retailers.

## GitHub Pages
Upload the files in this package to the repository root, preserving the `assets/` folder.

The brand logos are loaded from `cdn.simpleicons.org`. For a production client deployment, replace those URLs with brand-approved logo assets when the retailer has the appropriate usage rights.
