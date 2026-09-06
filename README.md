# FalconScale — Turnkey Launch & Funnel Infrastructure

> High-converting, modern, dark-mode agency landing page and interactive client preview engine engineered for B2B conversion, fast global edge delivery, and instant Vercel deployment.

![Vercel Ready](https://img.shields.io/badge/Vercel-Deploys%20Instantly-black?style=flat-square&logo=vercel)
![HTML5 / Tailwind](https://img.shields.io/badge/Architecture-Static%20Edge%20Ready-090a0f?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-emerald?style=flat-square)

---

## Overview

**FalconScale** is an elite digital launch and growth infrastructure agency that builds turnkey challenge funnels, dynamic landing pages, and marketing pipelines for high-ticket online creators and coaches.

This repository contains the complete production-grade marketing architecture:
1. **Agency Landing Page (`index.html`)**: Vercel/Linear dark-mode aesthetic with live sprint capacity tracker, interactive ROI / Revenue simulator, editorial systems overview, comparison matrix, 3-step launch architecture, and high-converting inquiry capture.
2. **Client Preview Funnel (`demo.html`)**: Fully functional, interactive 3-step VIP challenge funnel simulation (Opt-In -> VIP Upgrade -> Attendee Portal & Workbook Access) with instant state switching.

---

## Repository Structure

```text
Falconscale/
├── index.html         # Main FalconScale agency landing page & ROI simulator
├── demo.html          # Interactive client preview: 3-step VIP Challenge Funnel flow
├── vercel.json        # Static routing, clean URLs, and HTTP security headers
├── .gitignore         # Standard git exclusion rules
└── README.md          # Repository overview and deployment guide
```

---

## Key Features & Design Directives

- **Obsidian Dark-Mode Aesthetic**: Grounded in `#090a0f` obsidian base, hairline borders (`rgba(255, 255, 255, 0.08)`), ice-white typography (`#f8fafc`), subdued slate labels (`#94a3b8`), and surgical electric emerald (`#10b981`) accents.
- **Interactive ROI / Revenue Simulator**: Real-time slider engine calculating opt-in volume, VIP upsell revenue, backend sales, total launch gross, and projected ROI multiple with zero page reloads.
- **Editorial Systems Layout**: Asymmetrical, high-density breakdown of Edge Funnel Infrastructure, Psychological Launch Copy, and High-Impact Creative Suite.
- **Interactive Funnel Flow Teaser**: Embedded interactive preview card showing the live challenge journey, linking directly to `demo.html`.
- **High-Converting Lead Capture**: Inquiry form with real-time validation, subtle focus states, and interactive submission toast notifications.
- **Zero Build Dependencies**: Native HTML5, Tailwind CSS (via CDN with custom color tokens), Lucide Icons, and vanilla JavaScript. Deploys seamlessly without `npm install` or compilation delays.

---

## Deploy to Vercel (1-Click or Git Push)

### Method 1: Push to GitHub & Connect to Vercel (Recommended)
1. Push this repository to GitHub:
   ```bash
   git init
   git add .
   git commit -m "feat: initial FalconScale agency landing page and funnel demo"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/falconscale.git
   git push -u origin main
   ```
2. Log into [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your `falconscale` repository.
4. Leave all build settings as **Default / Other** (no build command needed).
5. Click **Deploy**. Vercel will deploy in `< 5 seconds`.

### Method 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## Local Development & Preview

Because this is a zero-dependency static build, you can preview it with any local HTTP server:

```bash
# Using Python 3
python -m http.server 8080

# Or using Node npx
npx serve .
```

Open `http://localhost:8080/index.html` or `http://localhost:8080/demo.html` in your browser.

---

## Contact & Inquiries

- **Agency Inquiries**: [falconscale.inquiries@gmail.com](mailto:falconscale.inquiries@gmail.com)
- **Website**: [falconscale.com](https://falconscale.com)
- **Focus**: Turnkey 5-Day Challenge Funnels, VIP Upsell Engines, and High-Ticket Infrastructure.
