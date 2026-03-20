<div align="center">

# 🟢 Zerodha Clone — Upgraded UI

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-View_Project-387ED1?style=for-the-badge)](https://mohanx-0001.github.io/zerodha-clone)
[![GitHub](https://img.shields.io/badge/GitHub-MOHANX--0001-181717?style=for-the-badge&logo=github)](https://github.com/MOHANX-0001)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

<br/>

> **A pixel-perfect, upgraded clone of the Zerodha landing page** — rebuilt from scratch with a modern design system, better typography, smooth scroll animations, and a fully responsive layout.  
> No frameworks. No build tools. Pure HTML + CSS + Vanilla JS.

<br/>

![Zerodha Clone Preview](https://zerodha.com/static/images/landing.png)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [What's Upgraded](#-whats-upgraded)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Sections](#-sections)
- [Local Setup](#-local-setup)
- [Deployment](#-deployment)
- [Author](#-author)

---

## 🧠 Overview

This is an **upgraded clone of the Zerodha homepage** — India's largest stock brokerage platform. The original layout was recreated and significantly improved with a proper design system, better component structure, modern typography, and polished animations.

Built as a frontend practice project to sharpen skills in:
- Semantic HTML5 structure
- CSS layout systems (Grid, Flexbox)
- CSS custom properties (design tokens)
- Scroll-triggered animations using `IntersectionObserver`
- Responsive design for all screen sizes

---

## 🌐 Live Demo

> 🔗 **https://mohanx-0001.github.io/zerodha-clone**

---

## ✨ What's Upgraded

| Area | Original | Upgraded |
|---|---|---|
| **Typography** | Inter (generic) | Bricolage Grotesque (headings) + DM Sans (body) |
| **Hero** | Plain image + centered text | Two-column split, live status badge, 3-stat bar |
| **Trust section** | Bare paragraphs | Icon cards with hover lift animations |
| **Pricing** | Small floating SVG images | ₹0 / ₹0 / ₹20 pricing cards with highlight |
| **Education** | Raw paragraphs | Numbered cards (01/02) with structured layout |
| **Footer** | Basic grid | Icon button socials, clean link columns |
| **Animations** | None | Scroll-reveal with `IntersectionObserver` |
| **Nav** | Basic fixed bar | Blur backdrop, scrolled state, mobile hamburger |
| **Design tokens** | Hardcoded values | CSS variables for full consistency |
| **Responsive** | Partially broken | Fully responsive — mobile, tablet, desktop |

---

## ✨ Features

| Feature | Details |
|---|---|
| **Scroll Reveal** | Sections animate in (fade + slide) as you scroll, powered by `IntersectionObserver` |
| **Sticky Nav** | Fixed navbar with blur backdrop that darkens and gains shadow on scroll |
| **Mobile Hamburger** | Slide-in mobile nav with animated open/close toggle |
| **Hero Stats Bar** | 1.5+ Cr customers · ₹4.5+ L Cr equity · 15% daily volume — displayed as live stats |
| **Trust Cards** | 4 feature cards with icons, hover lift, and smooth border transitions |
| **Pricing Cards** | Clean card layout with highlighted ₹20 flat fee card |
| **Education Cards** | Numbered 01/02 card layout for Varsity and TradingQ&A |
| **Social Icon Grid** | 7 social platforms with hover states in the footer |
| **Full Legal Section** | Complete SEBI/regulatory disclaimer with styled links |
| **Policy Bar** | 9-item policy footer row matching the real Zerodha site |
| **CSS Design Tokens** | All colors, shadows, radii, and spacing via CSS custom properties |
| **Fully Responsive** | Mobile-first layout tested at 320px → 1440px+ |

---

## 🛠️ Tech Stack

```
Markup      →  HTML5 (semantic structure)
Styling     →  CSS3 (Grid, Flexbox, Custom Properties, Transitions)
Scripting   →  Vanilla JavaScript (ES6+)
Fonts       →  Google Fonts — Bricolage Grotesque + DM Sans
Icons       →  Remixicon 4.5
Images      →  Zerodha CDN (zerodha.com/static/images)
Hosting     →  GitHub Pages
```

**No frameworks. No build tools. No npm. No dependencies.**

---

## 📁 Project Structure

```
zerodha-clone/
│
├── index.html        # Full page markup — all sections
└── index.css         # All styles — design system, layout, animations
```

Clean and simple. Everything in two files.

---

## 📄 Sections

### 🏠 Hero
Two-column layout — headline on the left with a live "Trusted by 1.5+ crore investors" badge, animated CTA button, and a 3-stat bar (Active Customers · Equity Investments · Daily Retail Volume). Platform screenshot on the right.

### 🛡️ Trust (Why Zerodha)
Four feature cards — Customer-first · No Spam · Zerodha Universe · Do Better with Money — each with a blue icon badge and hover animation. Followed by a press logo bar ("As featured in").

### 💰 Pricing (Unbeatable Pricing)
Three pricing cards in a grid layout displaying ₹0 account opening, ₹0 equity delivery, and ₹20 flat fee for intraday/F&O — the ₹20 card is highlighted in brand blue.

### 📚 Education (Free & Open)
Two-column section with the Varsity illustration and two numbered edu-cards (01 — Varsity, 02 — TradingQ&A) with descriptions and link buttons.

### 🚀 Open Account CTA
Centered call-to-action with a radial gradient background glow, headline, subtitle, and sign-up button.

### 🦶 Footer
Four-column grid — brand + social icons, Company links, Support links, Account links — followed by full SEBI legal disclaimer and a 9-item policy bar.

---

## ⚙️ Local Setup

No build step. No install. Just open.

```bash
# 1. Clone the repository
git clone https://github.com/MOHANX-0001/zerodha-clone.git

# 2. Navigate into the folder
cd zerodha-clone

# 3. Open in browser
open index.html
# or drag index.html into any browser
```

> 💡 For the best experience, use the **VS Code Live Server** extension so you get hot reload while editing.

---

## 🚀 Deployment

Deployed via **GitHub Pages** — free, instant, zero-config.

```bash
# Push to main → auto-deploys to:
# https://<your-username>.github.io/zerodha-clone
```

**Steps:**
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Visit `https://<your-username>.github.io/zerodha-clone`

---

## 📝 Disclaimer

This project is built **purely for educational and practice purposes**. It is not affiliated with, endorsed by, or connected to Zerodha Broking Ltd. in any way. All brand assets (logo, images) belong to Zerodha and are used only for UI recreation practice.

---

## 👤 Author

**Pawar Mohan Suresh**  
BSc Computer Science · Savitribai Phule Pune University (SPPU) · 2023–2026

| | |
|---|---|
| 🐙 GitHub | [github.com/MOHANX-0001](https://github.com/MOHANX-0001) |
| 💼 LinkedIn | [linkedin.com/in/mohan-pawar-dev](https://www.linkedin.com/in/mohan-pawar-dev/) |
| ✉️ Email | mohanpawarx1010@gmail.com |

---

<div align="center">

**Built by Mohan Pawar · 2026**

*If you found this useful, drop a ⭐ on the repo!*

</div>
