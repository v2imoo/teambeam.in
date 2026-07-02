# TeamBeam India — teambeam.in

Static marketing site for **TeamBeam** (India + rest-of-world). One TeamBeam, two homes — sister site: **teambeam.us**.
Self-contained HTML, clean URLs, full SEO + AI-search readiness, ready for **GitHub → Cloudflare Pages**.

## What's inside
- 147 content pages + `go.html` (region splitter) + `404.html`
- 12 Insights articles (`resources-insights-*.html`) with Article + BreadcrumbList JSON-LD
- `sitemap.xml`, `robots.txt` (AI crawlers welcomed), `_redirects`, `_headers`, `site.webmanifest`
- Icons (`favicon.svg`, `favicon.ico`, `icon-180/192/512.png`), `og-cover.png`

## Brand
- Fonts: Bricolage Grotesque (display), Plus Jakarta Sans (body), Space Mono (mono)
- Colours: Navy #0D2137 · Blue #1565C0 · Amber #E8940F (+ accent vibrancy layer)
- Logo: text lockup `Λ TEAMBEAM OUTINGS` (OUTINGS in amber) — do not replace with an image

## Deploy to Cloudflare Pages
1. Push this folder's contents to a GitHub repo (files at **repo root** — `index.html` at top level).
2. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git** → select the repo.
3. Framework preset **None**, Build command **empty**, Build output directory **`/`** → **Deploy**.
4. Add custom domain **teambeam.in** (and `www` if wanted).

Clean URLs (`/what-we-do`) are served automatically by Cloudflare Pages from the matching `.html`.
`_redirects` maps any `*.html` hits to their clean URL (301) plus `/home /tools /insights /podcast`.

## Before go-live
- Paste real Google Form URLs into the contact pathways + Partnerships-Apply (currently mailto fallbacks).
- Add podcast platform links on `resources-podcast`.
