# Portfolio — Integration Engineer, Health Tech

[![Live Site](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-black?style=flat-square&logo=github)](https://jythakur.github.io)
[![FHIR R4](https://img.shields.io/badge/FHIR-R4-blue?style=flat-square)](https://hl7.org/fhir/R4/)
[![HL7](https://img.shields.io/badge/HL7-v2.5-green?style=flat-square)](https://www.hl7.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)

> Personal portfolio of an Integration Engineer specialising in healthcare interoperability, HL7 & FHIR, and seamless data pipelines across clinical, EHR, and health-tech ecosystems.

---

## 👤 About

Integration Engineer with hands-on delivery experience across 25+ provider facilities — from HL7 interface design and EMR implementation to AI data pipelines and FHIR R4 exploration. Based in India.

**Core focus areas:**
- HL7 v2.5 integrations (ADT, ORU, ORM, DFT, SIU) across lab, EMR, PACS/RIS, and LIS environments
- End-to-end EMR interface implementation using Allscripts, Mirth Connect, and proprietary engines
- FHIR R4 / US Core 6.1 — resource structures, RESTful APIs, and US healthcare interoperability
- ETL pipeline design, SQL-driven data engineering, and AI training data quality

---

## 🗂️ Repository Structure

```
portfolio/
├── index.html                    ← Main portfolio (rename from index_portfolio.html)
├── 404.html                      ← Custom 404 page
├── README.md                     ← This file
├── fhir-platform/
│   ├── index.html                ← FHIR Platform landing page
│   ├── fhir-client-platform.html ← Client / EHR platform
│   ├── fhir-vendor-platform.html ← Vendor / Lab platform
│   ├── fhir-bridge.js            ← Messaging layer
│   ├── DEPLOYMENT_GUIDE.html     ← GitHub Pages setup guide
│   ├── README.md                 ← FHIR platform documentation
│   └── LICENSE
└── .nojekyll                     ← Prevents GitHub Pages Jekyll processing
```

---

## 📄 Pages & Sections

The portfolio is a single-page HTML site with smooth-scroll navigation across the following sections:

| Section | ID | Description |
|---|---|---|
| Hero | `#hero` | Headline, tagline, and call-to-action links |
| Expertise | `#expertise` | Core disciplines and technical specialisms |
| Experience | `#experience` | Professional timeline with role details |
| Projects | `#projects` | 7 featured projects with modal detail view |
| Mirth Tutorial | `#mirth-tutorial` | Mirth Connect 4.5.2 integration guide |
| FHIR Platform | `#fhir-platform` | Open-source FHIR R4 learning platform |
| Skills | `#skills` | Technologies, platforms, and tooling |
| Education | `#education` | Academic qualifications |
| About | `#about` | Resume preview and personal summary |
| Contact | `#contact` | Email, LinkedIn, GitHub |

---

## 🛠️ Tech Stack

**Integration & Interoperability**
HL7 v2.5 · FHIR R4 · Mirth Connect 4.5.2 · Allscripts EMR · PACS / RIS / LIS · TCP/IP / MLLP · SFTP · API

**Data & Engineering**
SQL (Oracle / MySQL) · Python · Pandas / NumPy · ETL Pipelines · Machine Learning · CRON / Quartz

**Standards & Compliance**
ICD-10 · SNOMED CT · LOINC · HIPAA / GDPR · US Core 6.1 · USCDI v3

**Web**
HTML · CSS · JavaScript · BroadcastChannel API · localStorage

---

## 🔬 Featured Projects

| # | Project | Type |
|---|---|---|
| 01 | Healthcare EMR Integration — Allscripts Implementation | Professional |
| 02 | Strategic EHR Interoperability & Vendor Alignment | Professional |
| 03 | Mirth Connect 4.5.2: Real-Time HL7 Pipeline | Independent |
| 04 | AI Training Data Pipeline — Healthcare QA Readiness | Professional |
| 05 | ETL & ML Pipeline — Population Data Analysis | Internship |
| 06 | Marketing Mix Modelling & Campaign Analytics | Professional |
| 07 | FHIR R4 — Self-Driven Learning & Implementation Exploration | Independent |

### Project 07 — FHIR R4 Learning Platform (highlighted)

The most technically involved independent project — a fully browser-based, zero-backend FHIR R4 practice environment hosted separately under `fhir-platform/`.

**What it does:**
- Simulates the complete clinical order-to-result workflow between a Client (EHR) and Vendor (lab/radiology) platform in two browser tabs
- No server, no npm, no installation — open the HTML file and it works
- Real FHIR resources flow across tabs via BroadcastChannel + localStorage

**Technical highlights:**
- FHIR R4 IntelliSense engine — VSCode-style `Ctrl+Space` autocomplete for 18 resource types
- Live HL7 validation via `hapi.fhir.org/$validate` (same engine as inferno.healthit.gov)
- 158+ clinical code search across LOINC · SNOMED CT · ICD-10 · RxNorm · CPT · RadLex with fuzzy matching
- US Core 6.1 profiles, USCDI v3 data classes, correct system URIs, MRN identifier parsing
- Patient demographics parsed from real FHIR Patient JSON (`name[]`, `identifier[]` MRN, DOB, gender)
- Open source under MIT licence

**Live demo:** `https://jythakur.github.io/fhir-platform-sandbox/`
**Separate repo:** `https://github.com/JyThakur/fhir-platform-sandbox`

---

## 🚀 Deployment

This portfolio is deployed via **GitHub Pages** from the `main` branch root.

### Deploy steps

```bash
# 1. Clone or create the repo
git clone https://github.com/JyThakur/JayThakur_HealthTechIntegration_UnitedKingdom

# 2. Add all files
git add .
git commit -m "Initial portfolio deploy"
git push origin main

# 3. Enable GitHub Pages
# Settings → Pages → Source: main / (root) → Save
```

**Live URL:**
```
https://jythakur.github.io/JayThakur_HealthTechIntegration_UnitedKingdom/
```

### File naming note

The main portfolio file is saved as `index.html` in this repository and the FHIR platform is named as `fhir_platform_main_page.html`.

---

## ✨ Portfolio Features

- **Single-page** with smooth-scroll navigation and active-link highlighting
- **Responsive** — mobile, tablet, and desktop layouts with a hamburger menu on small screens
- **Scroll reveal** animations — sections and elements fade in as you scroll (IntersectionObserver)
- **Animated skill bars** — trigger when the skills section enters the viewport
- **Project modal** — click any project row to open a full detail overlay with achievements and tags
- **Dark/light design** — warm off-white (`#f0ede6`) with deep ink (`#111410`) and accent green (`#1a6e52`)
- **Custom 404 page** — branded page matching the portfolio design with quick navigation links
- **Print stylesheet** — clean output if the page is printed or saved as PDF
- **Reduced motion** — respects `prefers-reduced-motion` for accessibility
- **Forced colours** — supports high-contrast mode

---

## 📚 Education

| Degree | Institution | Location | Grade |
|---|---|---|---|
| MSc Data Science | Kingston University London | London, UK | Merit |
| PG Diploma in Data Science | IIIT Bangalore | Bangalore, India | CGPA 3.29/4.0 |
| BEng Computer Science | NBN Sinhgad School of Engineering | Pune, India | 6.64/10.0 |

---

## 🔗 Links

| Platform | URL |
|---|---|
| Portfolio | https://jythakur.github.io/JayThakur_HealthTechIntegration_UnitedKingdom/ |
| LinkedIn | https://www.linkedin.com/in/jaythakur37/ |
| GitHub | https://github.com/JyThakur |
| FHIR Platform | https://jythakur.github.io/fhir-platform-sandbox/ |

---

## 📄 Licence

MIT — feel free to use the structure and layout as a reference for your own portfolio.

---

<div align="center">
<em>Built for clarity, maintained with care · London, UK · 2026</em>
</div>
