# Changelog — lofi-mandala-site

All notable changes to the website are documented here.

---

## [Unreleased]

---

## 2026-06-05

### Added
- `robots.txt` — permissive crawl rules with sitemap pointer
- `sitemap.xml` — all 5 pages listed with priority and change frequency
- `og:image:alt` and `twitter:image:alt` to index.html
- `twitter:image:alt` to index.html
- `apple-itunes-app` meta tag to index.html — enables iOS Safari Smart App Banner
- `WebSite` and `Organization` JSON-LD schemas to index.html
- `downloadUrl` (App Store) added to `MobileApplication` JSON-LD schema
- Full meta tags to all secondary pages (description, canonical, Open Graph, Twitter Card, favicon, theme-color): privacy.html, support.html, music-licensing.html, newsletter.html

### Fixed
- index.html: `<div class="app-name">` promoted to `<h1>` for heading hierarchy
- index.html: page content wrapped in `<main>` landmark element
- index.html: footer links wrapped in `<nav aria-label="Footer">`
- index.html: App Store URL changed from Canada-specific `/ca/` to universal `/app/id6764457673`

---

## 2026-05-24

### Added
- `app-ads.txt` — AdMob publisher verification file for Google Play Console
- Privacy policy updated to reflect AdMob integration
