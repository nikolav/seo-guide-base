# seo quick checklist

## 🚨 indexing & crawlability (seo blockers)
- ✅ pages indexed in google
- request indexing for important pages
- investigate “discovered – currently not indexed”
- ensure pages have unique, valuable content
- ✅ no blocking robots.txt rules, allow*
- allow crawling for public routes:
- test with gsc → robots.txt tester
- ✅ no accidental noindex
- use noindex only for: admin pages, search results pages, thank-you / private flows
- ✅ xml sitemap valid & submitted
- generate sitemap automatically (framework or build step)
- submit in gsc → sitemaps
- exclude: !index pages, redirects, 404
- ✅ ssr / prerendered html visible
- prerender content if possible
- use dev utils to bot preview content
- ✅ canonicals correct
- enforce single canonical url, present on every indexable page
- use canonicals for duplicates, redirect to canonical version
- ✅ no crawl errors or loops
- optimal gsc → crawl stats
- no errors, warnings, 404s

## ⚡ 2. performance & core web vitals
- 🟠 lcp > 2.5s (slow main content load)
- preload hero image
- serve images as webp / avif
- enable ssr / prerender
- reduce ttfb (cdn, caching, fast hosting)
- 🟠 inp > 200ms (sluggish interactions)
- split js bundles (route-level)
- defer non-critical scripts
- break long tasks (settimeout, requestidlecallback)
- remove unused js & libraries
- 🟠 cls > 0.1 (layout jumping)
- always set width & height on images
- reserve space for embeds/ads
- `font-display: swap` @font-face
- avoid injecting content above the fold
- 🟠 High JS Blocking Time
- Remove unused JS
- Load analytics after interaction
- Prefer SSR over client-only rendering
- Avoid heavy hydration on first load
- 🟠 Unoptimized Images
- Compress images
- Use responsive images (srcset, sizes)
- Lazy-load below-the-fold images
- Preload only one critical image
- 🟠 Poor Caching / Network
- Enable Brotli / gzip
- Cache static assets (Cache-Control)
- Use CDN
- Reduce redirects
- 🟠 Client-only SPA (SEO risk)
- Enable SSR or prerender public pages
- Ensure content is visible without JS
- Verify rendered HTML with Googlebot UA

## 📱 3. Mobile-Friendliness
