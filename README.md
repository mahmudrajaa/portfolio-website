# Raja Mohammed — Portfolio Website

Definitive professional portfolio for **Raja Mohammed** — Senior Cloud & AI Automation Architect (Azure · AWS · Microsoft Sentinel · Generative AI).

A single self-contained static site: premium enterprise design, adaptive dark/light theme, interactive architecture diagrams, command palette (⌘K), animated metrics, filterable case studies, and full SEO / Open Graph / JSON-LD.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire site (HTML + CSS + JS inline, zero build step) |
| `Raja_Mohammed_Resume.pdf` | Résumé served by the download buttons |
| `robots.txt` / `sitemap.xml` | SEO crawl directives |
| `portrait.jpg` | **Add this** — your professional photo (see below) |
| `og-image.png` | **Add this** — 1200×630 social share image (see below) |

## Before you publish — 3 quick edits

1. **Add your photo.** Save a professional headshot as `portrait.jpg` in this folder, then in `index.html` find the `.portrait .ph` placeholder block and replace it with:
   ```html
   <img src="portrait.jpg" alt="Raja Mohammed" style="width:100%;height:100%;object-fit:cover">
   ```
2. **Set your real domain.** Search-and-replace `https://rajamohammed.vercel.app/` throughout `index.html`, `robots.txt`, and `sitemap.xml` with your actual Vercel/custom URL.
3. **Add a social image** (optional but recommended): a 1200×630 `og-image.png` for LinkedIn/Twitter link previews.

## Deploy to GitHub + Vercel

```bash
# 1. From this folder, create a repo
git init
git add .
git commit -m "Portfolio website"
git branch -M main
git remote add origin https://github.com/<you>/portfolio.git
git push -u origin main
```

Then on **Vercel**: New Project → Import the GitHub repo → Framework Preset **Other** → Root Directory **/** → Deploy. No build command needed (it's a static site). Add a custom domain under Project → Settings → Domains.

> Alternatively, GitHub Pages: push to `main`, enable Pages from the repo root.

## Editing content

All case-study and tech-stack content lives in the `<script>` `DATA` block near the bottom of `index.html` (the `CASES` and `TECH` arrays) — edit there to add/change projects; the cards, filters, and modals regenerate automatically.

---
All content is drawn from Raja Mohammed's own résumés and portfolio; metrics (e.g. −60–70% handling time, −30–40% inference cost) are reproduced as stated in those source documents.
