# Therapeia Website

Official marketing website for **Therapeia** — an AI-Driven Neurological Health Navigator.

## Overview

Therapeia is a precision medicine platform built on the **Neurological Functional Baseline (NFB)**, an intra-individual longitudinal monitoring system that detects neurological changes before clinical presentation.

**Live Site:** https://pythia-therapeia.netlify.app/

## Features

- **Responsive Design** — Mobile-first, works on all devices
- **Professional Branding** — Teal (#1A5C6B) and Gold (#B8962E) color scheme
- **Multi-Page Structure** — Home, About, Services, Ecosystem, Research, Contact, Privacy, Terms
- **Board of Advisors** — Nine expert advisors across neurology, surgery, insurance, and AI
- **HIPAA-Compliant** — Privacy and Terms of Service with healthcare-specific language
- **FHIR R4 Ready** — Healthcare interoperability standards

## Pages

- **Home** (`index.html`) — Hero section with platform overview and CTAs
- **About** — Neurological Functional Baseline concept and key differentiators
- **Services** — Pythia Field, Pythia Navigator, Therapeia Platform
- **Ecosystem** — Board of Advisors and clinical partners
- **Research** — Publications, case studies, and clinical evidence
- **Contact** — Contact form for inquiries
- **Privacy Policy** (`privacy.html`) — HIPAA-compliant privacy practices
- **Terms of Service** (`terms.html`) — Legal terms and medical disclaimers

## Technology Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Hosting:** Netlify (automatic deployments from GitHub)
- **Design System:** Custom CSS with responsive grid layouts
- **Fonts:** Georgia (headings), Open Sans (body)

## Development

### File Structure

therapeia-website/
├── index.html # Home page
├── privacy.html # Privacy Policy
├── terms.html # Terms of Service
├── src/
│ ├── css/
│ │ └── style.css # Main stylesheet
│ ├── js/
│ │ └── script.js # Interactive features
│ └── images/
│ └── Pythia-Therapeia-web-image.png
├── LICENSE # MIT License
└── README.md # This file

### Local Development

1. Clone the repo:
```bash
   git clone https://github.com/miki0398/therapeia-website.git
   cd therapeia-website
```

2. Open `index.html` in your browser (no build process required)

3. Make changes and test locally

4. Commit and push to GitHub:
```bash
   git add .
   git commit -m "Your message"
   git push origin main
```

Netlify will auto-deploy on every push.

## Deployment

This site is deployed to **Netlify** and automatically rebuilds on every GitHub push to the `main` branch.

**Deployment Status:** [![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-BADGE-ID/deploy-status)](https://pythia-therapeia.netlify.app/)

## Brand Colors

- **Primary Teal:** `#1A5C6B` — Trust, healthcare, stability
- **Secondary Gold:** `#B8962E` — Premium, innovation, warmth
- **Accent Lavender:** `#E6E6FA` — Patient voice, care

## Legal

- **License:** MIT License
- **Privacy:** See [Privacy Policy](privacy.html)
- **Terms:** See [Terms of Service](terms.html)

## Contact

For questions about the website or Therapeia platform:

- **Email:** hello@therapeia.ai
- **GitHub:** [miki0398/therapeia-website](https://github.com/miki0398/therapeia-website)

---

**Built with ❤️ by Therapeia Inc.** | 2026
