# Abhirav Joshi — GTM Engineer Portfolio

Personal portfolio site built from the `gtm-engineer-corporate` template. The theme
(Fraunces + Archivo, ivory / ink / cobalt / bronze, scroll reveals, counters, marquee)
is unchanged; only the content differs. Single static `index.html`, no build step.

## Before deploying

1. Domain is set to `https://abhiravjoshi.xyz/` in `index.html`, `robots.txt` and `sitemap.xml`.
2. `og.png` (1200×630) is the social preview card. To regenerate it after changing the
   hero numbers, open `og-source.html` at a 1200×630 viewport and screenshot it.
3. When LinkedIn / GitHub should be public, add them to the `contact-links` block and
   as a `sameAs` array in the JSON-LD.
4. Numbers to keep current: gym members (230), B2B deals (25), leads (300+), monthly
   revenue (₹4L). They appear in the hero, metrics band, case studies and experience.

## Run locally

```bash
npm install
npm start          # serves on http://localhost:3000
```

Or open `index.html` directly in a browser.

## Deploy

Any static host works: Vercel, Netlify, Cloudflare Pages, GitHub Pages. Drop the folder
in and point the domain at it.
