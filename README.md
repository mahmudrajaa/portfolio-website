# Raja Mohammed — Portfolio Website

Definitive professional portfolio for **Raja Mohammed** — Senior Cloud & AI Automation Architect (Azure · AWS · Microsoft Sentinel · Generative AI).

**Live:** https://mahmudrajaa.github.io/portfolio-website/

A single self-contained static site: premium enterprise design, adaptive dark/light theme, interactive architecture diagrams, command palette (⌘K), animated metrics, filterable case studies, and full SEO / Open Graph / JSON-LD. No build step, no dependencies.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire site (HTML + CSS + JS inline) |
| `Raja_Mohammed_Resume.pdf` | Résumé served by the download buttons |
| `robots.txt` / `sitemap.xml` | SEO crawl directives |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll and serve files as-is |
| `portrait.jpg` | **Add this** — your professional photo (see below) |
| `og-image.png` | **Add this** — 1200×630 social share image (see below) |

## Recommended edits

1. **Add your photo.** Save a professional headshot as `portrait.jpg` in the repo root, then in `index.html` find the `.portrait .ph` placeholder block and replace it with:
   ```html
   <img src="portrait.jpg" alt="Raja Mohammed" style="width:100%;height:100%;object-fit:cover">
   ```
2. **Add a social share image** (recommended for LinkedIn/Twitter previews): a 1200×630 `og-image.png` in the repo root. The `og:image` meta tag already points to it.

> Site URLs are already set to `https://mahmudrajaa.github.io/portfolio-website/`. If you later add a custom domain, search-and-replace that URL across `index.html`, `robots.txt`, and `sitemap.xml`.

## How it's hosted (GitHub Pages)

This repo is published via **GitHub Pages** from the `main` branch. To change settings: repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `/ (root)`.

Any push to `main` republishes automatically within a minute or two.

```bash
# make edits, then:
git add .
git commit -m "Update portfolio"
git push
```

## Editing content

All case-study and tech-stack content lives in the `<script>` `DATA` block near the bottom of `index.html` (the `CASES` and `TECH` arrays). Edit there to add or change projects — the cards, filters, and modals regenerate automatically.

---
All content is drawn from Raja Mohammed's own résumés and portfolio; metrics (e.g. −60–70% handling time, −30–40% inference cost) are reproduced as stated in those source documents.
