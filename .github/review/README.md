# Landing page review

Captured at 390 × 900 and 1280 × 900 CSS-pixel viewports, full page, device scale 1, in local headless Chrome. Files prefixed `landing` show `/`; files prefixed `privacy` show `/privacy/`.

- HTML: html-validate 11.15.0, recommended defaults, **0 errors / 0 warnings** on both pages.
- Lighthouse 13.4.1: mobile default and desktop preset, localhost, **100 performance / 100 accessibility / 100 best practices / 100 SEO** for both pages. Scores and timing metrics: `lighthouse.json`. These are local lab measurements, not live GitHub Pages measurements.
- Browser: both pages at 360, 390, 700, 1280, and 1440px; no horizontal overflow. At 390px, 200% root text size also fits. Skip link is the first Tab stop and Enter focuses main. All image and fragment targets resolve. No scripts, forms, cookies, or third-party requests. Details: `browser-checks.json`.
- Policy: inner HTML compared byte for byte against `origin/main`; unchanged. `privacy.md` and `CNAME` also unchanged. Header, footer, and CSS match exactly between pages.
- Inline page bytes: landing 36,405; privacy 35,639. No external page assets. Screenshots are review evidence only.

To rerun HTML checks with an installed validator: `html-validate index.html privacy/index.html`.

For Lighthouse, serve locally, then run `lighthouse http://127.0.0.1:8765/ --chrome-flags="--headless" --only-categories=performance,accessibility,best-practices,seo`. Repeat with `--preset=desktop` and `/privacy/`.
