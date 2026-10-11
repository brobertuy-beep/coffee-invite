# Insight Tax landing page

Single-page site for Insight Tax (insightax.com.au), Robert Avey, CPA and Registered Tax Agent 75496000. Static HTML, no build step. Upload the `insight-tax/` folder to any static host.

## Files
- `index.html`: the full page (inline CSS and JS)
- `assets/brand/insightax-logo.png`, `assets/brand/insightax-logo-light.png`: the practice's logo (light version has white lettering for the footer)
- `assets/brand/tpb-registered.png`, `cpa-australia.png`, `xero-certified-advisor.png`: credential badges supplied by the practice
- `assets/brand/tax-technology.webp`: photo used in the in-house software section
- `assets/brand/business-team.webp`: photo banner in the Business Tax group
- `assets/brand/scene-*.png`: the practice's service illustrations (Individual, Business, Income Tax Returns groups)
- `assets/brand/value-*.webp`: the practice's Affordable / Fast Turnaround / Problem Free graphics, cropped so the captions are live text
- `assets/favicon.svg`, `assets/apple-touch-icon.png`: browser and phone icons
- `assets/hero.svg`, `assets/expat.svg`: custom section illustrations
- `assets/illustrations/`: unDraw illustrations recoloured to the brand palette (services groups, steps, why, pricing, reviews, about avatar, FAQ, contact)
- `assets/og-image.png`: 1200x630 preview image for link sharing

## Fill in before going live (search the HTML for `OWNER:`)
1. ABN in the footer, and a link to the privacy statement.
2. Testimonials: the three reviews are samples. Replace with real client reviews (with permission) and delete the placeholder tags.
3. Pricing: add starting prices if desired, or keep the "Fixed fee" wording.
4. Headshot: replace the illustrated avatar in the About section with a photo of Robert.
5. Badges: the TPB, CPA Australia and Xero Certified Advisor badges are in place; keep them current with each body's logo rules.
6. Appointments use the practice's Google Form, embedded in the contact section and linked from the steps, FAQ and footer. The form must stay set to accept responses without sign-in for the embed to work. The separate "Get a quote" tab opens the visitor's email app addressed to info@insightax.com.au; connect a form service (Formspree, etc.) for direct submissions.
7. Software section: confirm the three claims about the in-house tax preparation software are accurate.
8. Expat section: confirm the practice is comfortable advertising foreign income and residency work.

## Design notes
Structure and feel follow the Bright!Tax homepage pattern: navy and orange palette, deadline banner, quote-first hero, trust strip, services grid, how-it-works steps, pricing cards, reviews, team, FAQ and quote form. The logo, badges and photo are the practice's own; the copy, layout and illustrations do not copy Bright!Tax material. Copy draws on the existing insightax.com.au content (tagline, Affordable / Fast Turnaround / Problem Free, services, extended support, about text). Services are grouped as on the current site: 01 Individual Tax Return, 02 Business Tax, 03 Income Tax Returns by structure, 04 Extended Support.

## Illustration licence
Files in `assets/illustrations/` are from unDraw (undraw.co) by Katerina Limpitsouni, sourced via the `undraw-svg` npm package. The unDraw licence allows free commercial use on websites without attribution; a courtesy credit is included in the footer anyway. It does not allow repackaging them into a competing illustration library.

## Mobile support
Tested with no horizontal scrolling at 280px (Galaxy Z Fold folded), 320, 360, 375, 390, 412 and 430px portrait, plus 568, 667 and 932px landscape. Includes iPhone safe-area padding for the sticky call/quote bar, 16px form inputs (no iOS zoom on focus), WebKit prefixes for the sticky blurred header, and a reduced comparison table on very narrow screens. Testing used Chromium device emulation; a quick check in Safari on a real iPhone before launch is still worthwhile.
