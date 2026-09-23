# Health & Fitness Calculators — Homepage Package

This folder contains the 4 files requested for the **Health & Fitness Calculators** site.

## Files

- **index.html** — The main homepage. Self-contained (fonts loaded from Google Fonts, everything else inline). Dark, luxury/premium theme (deep charcoal-green + champagne gold), with scroll-reveal animations, a drifting gradient hero, and hover micro-interactions on cards.
- **robots.txt** — Allows all crawlers, points to the sitemap.
- **sitemap.xml** — Single-URL sitemap for the homepage.
- **README.md** — This file.

## SEO / content notes

- **Target keyword:** "worked example calculators" — used in the `<title>`, meta description, meta keywords, H1, and repeated naturally through the H2 headings and body copy.
- **Anchor text link:** "free online calculators" appears **once**, only in the **second paragraph** of the article, linking to `https://calcumatix.com/calculators/`. No other link to this URL appears anywhere else on the page.
- **Word count:** the article body is **1,108 words**, structured semantically with `<article>`, `<h1>`–`<h3>`, and five worked-example blocks (BMI, TDEE/calories, macros, body fat, one-rep max).
- **Images:** since no photos were supplied, the page uses lightweight inline SVG line-icons (gold-stroke, on-theme) instead of external images — this keeps the page fast, licence-free, and visually consistent with the luxury palette. Swap these `<svg>` blocks for real photography any time by replacing the icon markup inside each `.card`.
- **No phone number or call button** was added, per your instruction.

## Before you publish

1. Replace `https://example.com/` in `index.html` (canonical tag), `robots.txt`, and `sitemap.xml` with your real domain.
2. Update the `<meta property="og:...">` tags if you want custom social-share previews.
3. If you add more pages later, add their URLs to `sitemap.xml`.
