# Portfolio QA — pre-deployment fixes

Branch: `portfolio/predeploy-qa-fixes-2026-10`
Base: `main`

## Completed in this branch

- Added the missing `#top` anchor used by the brand/home link.
- Corrected Book A Ride case-study image paths to the existing repository asset folder.
- Corrected all Skedoc case-study image paths to `assets/skedoc/`.
- Corrected the Skedoc return-to-home navigation paths and CYFOX cross-link.
- Corrected the EV Charging featured-cover path; removed Windows-style backslashes.
- Added asynchronous decoding to case-study imagery.
- Added lazy loading to below-the-fold imagery to reduce initial page work.

## Static QA performed

- Checked all 9 HTML pages in the site.
- Checked all local `src` and `href` references against repository paths.
- Checked in-page anchor targets.
- Checked image alt attributes.
- Checked duplicate HTML IDs.

Result: 0 missing local references, 0 missing anchor targets, 0 missing image alt attributes, and 0 duplicate IDs in the audited pages.

## Still required before production promotion

- Browser QA at desktop, tablet and mobile widths.
- Keyboard-only navigation and visible focus review.
- Reduced-motion check.
- Lighthouse / Core Web Vitals measurement.
- Confirm Vercel preview and domain behavior.

This report distinguishes automated/static checks from browser and production checks that have not been run here.
