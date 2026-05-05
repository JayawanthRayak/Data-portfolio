<div align="center">

# Jayawanth Rayakota — 3D Portfolio

### Senior Data Analyst · Data Engineer · Charlotte, NC

A single-file, immersive portfolio built with **Three.js**, animated with a particle field and drifting wireframe geometry, populated with four years of work across finance, banking, and healthcare data systems.

[![Live Site](https://img.shields.io/badge/▶_View_Live_Site-0a0a0a?style=for-the-badge&logoColor=white&labelColor=ffd84d&color=0a0a0a)](https://dataportfolio-g13r0kzcs-jayawanthrayakota-6349s-projects.vercel.app/)
[![Resume](https://img.shields.io/badge/Download_Resume-PDF-ffd84d?style=for-the-badge&logoColor=0a0a0a&labelColor=0a0a0a)](./Jayawanth_Rayakota_Resume.pdf)

![Three.js](https://img.shields.io/badge/Three.js-r128-000000?style=flat-square&logo=three.js&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Status](https://img.shields.io/badge/status-live-22c55e?style=flat-square)

</div>

---

## Live Demo

> **[dataportfolio-g13r0kzcs-jayawanthrayakota-6349s-projects.vercel.app](https://dataportfolio-g13r0kzcs-jayawanthrayakota-6349s-projects.vercel.app/)**

Best viewed on a desktop browser with WebGL support.

---

## About

This portfolio is a single-file, dependency-light static site — built from scratch and inspired by the editorial aesthetic of modern 3D portfolios. It distills four years of data engineering and analytics work into a scrollable, animated experience.

| | |
|---|---|
| **Owner** | Jayawanth Rayakota |
| **Role** | Senior Data Analyst · Data Engineer |
| **Experience** | 4+ years · Finance · Banking · Healthcare |
| **Stack focus** | AWS · Azure · Snowflake · PySpark · Python · SQL |
| **Education** | M.S. Computer Science · UNC Charlotte (2024–2025) |

---

## Highlights

- **Animated 3D background** — 1,200-particle field plus drifting wireframe icosahedron, octahedron, torus, and tetrahedron with mouse-parallax + scroll parallax.
- **Custom cursor** — dot + ring follower that grows on interactive elements.
- **Scroll-triggered reveals** — IntersectionObserver-driven entrance animations on every section.
- **Editorial typography** — Syne for display, Space Grotesk for accents, Inter for body. Dark + amber palette.
- **Resume-driven content** — every section pulls directly from the source resume so updates are mechanical.
- **Zero build step** — open `index.html` in any browser. Three.js loads via CDN.

---

## Sections

| # | Section | What's in it |
|---|---|---|
| 1 | **Hero** | Name, role tags, location, animated 3D scene, scroll hint |
| 2 | **About** | Bio, four-year stat panel (40% throughput · 60% manual reduction · 4 certs) |
| 3 | **Services** | Six cards: ETL, Analytics & BI, Cloud Architecture, Predictive Analytics, Governance, Performance |
| 4 | **Career** | Timeline — T. Rowe Price (Senior Data Analyst) · Kyndryl × Co-operative Bank (Data Engineer) |
| 5 | **Tech Stack** | Eight categorized cards + infinite marquee |
| 6 | **Education** | UNC Charlotte M.S. CS · 4 cloud / data certifications |
| 7 | **Contact** | Email, phone, social icons, resume download |

---

## Tech Stack

<div align="center">

**Frontend**
&nbsp;&nbsp;
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**3D & Animation**
&nbsp;&nbsp;
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white)

**Hosting**
&nbsp;&nbsp;
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## Project Structure

```
jayawanth-3d-portfolio/
├── index.html                          # Entire site — HTML, CSS, JS in one file
├── Jayawanth_Rayakota_Resume.pdf       # Downloadable resume (linked from nav + contact)
└── README.md                           # You are here
```

That's it. No `node_modules`, no build pipeline, no framework lock-in.

---

## Quick Start

### Run locally

```bash
# Just open it
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

…or, for nicer dev with auto-reload:

```bash
npx serve .
# http://localhost:3000
```

### Deploy to Vercel

```bash
npm i -g vercel
vercel
```

Or drag the folder onto the Vercel dashboard at [vercel.com/new](https://vercel.com/new).

### Deploy to GitHub Pages

Push to a repo, enable Pages on the `main` branch (root), done.

---

## Customization Guide

| What to change | Where |
|---|---|
| Accent color (amber `#ffd84d`) | Find/replace `#ffd84d` in `index.html` |
| Name / role / bio | Hero, About, and Contact sections in `index.html` |
| Career bullets | `<section id="career">` |
| Tech pills | `<section id="stack">` |
| Resume PDF | Replace `Jayawanth_Rayakota_Resume.pdf` |
| LinkedIn / GitHub URLs | Search `#linkedin` and `#github` placeholders |

---

## Performance Notes

- ~42 KB HTML/CSS/JS, no framework runtime.
- Three.js (~600 KB minified) is pulled from a CDN with HTTP cache hits across visits.
- Particle count is conservative (1,200) to stay smooth on integrated GPUs.
- Cursor effects auto-disable below 768 px to preserve mobile touch behavior.

---

## Contact

<div align="center">

**Jayawanth Rayakota**

[![Email](https://img.shields.io/badge/jayawanthrayakota@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayawanthrayakota@gmail.com)
[![Phone](https://img.shields.io/badge/+1_(980)_500--9375-22c55e?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+19805009375)
[![Location](https://img.shields.io/badge/Charlotte,_NC-blue?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

<div align="center">

Built with three.js · Hosted on Vercel · © 2026 Jayawanth Rayakota

</div>
