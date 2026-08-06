# Changelog — lofi-mandala-site

All notable changes to the website are documented here.

---

## [Unreleased]

### 6 August 2026 — Ambience audio licensing disclosure (PAI-249)

- `music-licensing.html` — narrowed the Suno claim from "All music tracks" to "The music tracks"; the blanket statement became inaccurate once Pixabay-sourced ambience audio shipped in app 2.0.0
- `music-licensing.html` — added Ambience Sounds section covering Pixabay sourcing, the Content License, and the no-standalone-redistribution position
- `music-licensing.html` — added intro paragraph distinguishing the two audio types and their separate licensing
- h1, meta description, OG and Twitter tags updated to "Music & Audio Licensing" — note the `<title>` tag still reads "Music Licensing", left deliberately unchanged pending a decision
- Last updated date bumped to August 2026

### 17 June 2026 — OneSignal push notification disclosure (PAI-204)

- `privacy.html` — added Push Notifications section explaining opt-in, push token collection, and per-platform opt-out instructions
- `privacy.html` — added OneSignal to Third-Party Services section with link to their privacy policy
- `privacy.html` — updated short version blurb to mention push notifications and opt-out
- Last updated date bumped to June 17, 2026

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
