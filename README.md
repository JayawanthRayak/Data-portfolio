# Jayawanth Rayakota — 3D Portfolio

A single-file, self-contained portfolio site inspired by the akashrmalhotra/3d-portfolio project — rebuilt from scratch with a Three.js animated background (particle field + drifting wireframe shapes), GSAP-style scroll reveals, custom cursor, and a dark + amber editorial aesthetic.

## Files
- `index.html` — the entire site (HTML, CSS, JS in one file, Three.js loaded from CDN)
- `Jayawanth_Rayakota_Resume.pdf` — your resume (linked from the nav button and contact section)

## How to use it

### Run locally
Just double-click `index.html`. It will open in your default browser. Three.js is loaded from a CDN, so you need an internet connection on first load.

### Deploy it
Drop the folder into any static host:
- **GitHub Pages** — push to a repo, enable Pages on the `main` branch (root).
- **Netlify / Vercel** — drag the folder onto their dashboard, done in seconds.
- **Cloudflare Pages** — same flow, free tier, fast.

## What to update before publishing

1. **LinkedIn URL** — search `#linkedin` in `index.html` and replace with your real LinkedIn profile URL.
2. **GitHub URL** — search `#github` in `index.html` and replace with your real GitHub URL.
3. (Optional) Update the favicon, OG meta tags, or color accent (`#ffd84d`) to match your brand.

## Sections included
- Hero with your name, role, location, and animated 3D background
- About — bio derived from your resume summary, plus stats (40% throughput, 60% manual reduction, 4 certs)
- Services — 6 cards: ETL, Analytics & BI, Cloud Architecture, Predictive Analytics, Governance, Performance
- Career timeline — T. Rowe Price (Senior Data Analyst) and Kyndryl/Co-operative Bank (Data Engineer) with bullets and tech callouts
- Tech stack — 8 categorized cards (Cloud, Languages, ETL, Databases, Big Data, Visualization, DevOps, Compliance) plus a marquee
- Education — UNC Charlotte, MS Computer Science (Jan 2024 – May 2025)
- Certifications — AWS Data Analytics, Azure Data Engineer, Snowflake SnowPro, Tableau Desktop
- Contact — email, phone, social icons, resume download

## Browser support
Modern Chrome / Firefox / Safari / Edge. Three.js requires WebGL (every browser since 2013).
