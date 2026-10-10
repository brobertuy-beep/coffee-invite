# Insight Tax landing page

Single-page site for Insight Tax (insightax.com.au), Robert Avey, CPA and Registered Tax Agent 75496000. Static HTML, no build step. Upload the `insight-tax/` folder to any static host.

## Files
- `index.html`: the full page (inline CSS and JS)
- `assets/logo.svg`, `assets/logo-light.svg`: eye-mark logo for light and dark backgrounds
- `assets/favicon.svg`, `assets/apple-touch-icon.png`: browser and phone icons
- `assets/hero.svg`, `assets/expat.svg`: custom section illustrations
- `assets/illustrations/`: unDraw illustrations recoloured to the brand palette (steps, pricing cards, software, extended support, contact)
- `assets/og-image.png`: 1200x630 preview image for link sharing
- `assets/appointment-form.pdf`: two-page client appointment form linked from the page (replace with the existing form if preferred, same filename)

## Fill in before going live (search the HTML for `OWNER:`)
1. ABN in the footer, and a link to the privacy statement.
2. Testimonials: the three reviews are samples. Replace with real client reviews (with permission) and delete the placeholder tags.
3. Pricing: add starting prices if desired, or keep the "Fixed fee" wording.
4. Headshot: replace the "RA" initials circle with a photo of Robert.
5. Badges: official TPB, CPA Australia and Xero Certified Advisor badges can replace the credential icons, used under each body's logo rules.
6. Form: it opens the visitor's email app addressed to info@insightax.com.au. Connect a form or booking service (Formspree, Calendly, etc.) for direct submissions.
7. Software section: confirm the three claims about the in-house tax preparation software are accurate.
8. Expat section: confirm the practice is comfortable advertising foreign income and residency work.

## Design notes
Structure and feel follow the Bright!Tax homepage pattern: navy and orange palette, deadline banner, quote-first hero, trust strip, services grid, how-it-works steps, pricing cards, reviews, team, FAQ and quote form. The Insight Tax name, logo, copy and illustrations are original. Copy draws on the existing insightax.com.au content (tagline, Affordable / Fast Turnaround / Problem Free, services list, extended support, about text).

## Illustration licence
Files in `assets/illustrations/` are from unDraw (undraw.co) by Katerina Limpitsouni, sourced via the `undraw-svg` npm package. The unDraw licence allows free commercial use on websites without attribution. It does not allow repackaging them into a competing illustration library.
