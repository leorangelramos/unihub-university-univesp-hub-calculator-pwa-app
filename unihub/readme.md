# 🎓 Univesp Student Hub (Unofficial PWA)

![Status](https://img.shields.io/badge/Status-Online-brightgreen?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-V2.0-blue?style=for-the-badge)
![SEO](https://img.shields.io/badge/SEO-Optimized-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

> **The Univesp Student's Swiss Army Knife:** A complete suite of tools to calculate grades, manage the updated curriculum grid, track internship hours, and consult the official 2026/2027 academic calendar.

### 🔗 [Access online: https://univespcalculadora.netlify.app/](https://univespcalculadora.netlify.app/)

---

## 💡 About the Project (Case Study)

> **Project Title:** Student Hub - Web App (PWA)

**Description:**
A Full-Stack (Frontend + Serverless) solution developed to solve the fragmentation of academic information by centralizing access to essential tools for a community of over 50,000 users.

### 🎯 The Technological Challenge

Centralize access to distributed institutional systems and calculation tools into a single, lightweight, mobile-first interface. The architectural goal was to mitigate a navigational logistical bottleneck that consumed thousands of combined user hours weekly.

### 🛠️ The Integrated Solution

- **Tech Stack:** Semantic HTML5, Modern CSS3, Vanilla JS (total focus on performance, efficient DOM manipulation, and instantaneous loading).
- **Architecture:** PWA (Progressive Web App) with Service Workers (`sw.js`) ensuring 100% Offline functionality.
- **Engagement:** Asynchronous integration with the **OneSignal** SDK for Push Notifications of critical deadlines.
- **Telemetry:** Event and conversion tracking via **Google Analytics 4 (GA4)**.
- **Data & Privacy:** State persistence via the `localStorage` API (no centralized backend, ensuring zero server costs and full LGPD/GDPR compliance).
- **Growth & SEO:** Advanced on-page SEO structuring, Open Graph, Twitter Cards, and JSON-LD Schema injection, guaranteeing high organic indexation on search engines.

---

## 🚀 Features of the Univesp Student Hub

The code operates as a complete **PWA (Progressive Web App)**. It can be natively installed on operating systems (Android/iOS/Desktop) and executes mathematical logic offline.

### 📊 Academic and Curricular Management

- **My Interactive Grid (New Interface):** Enhanced course selection and visual progress tracking.
  - _Supported Courses (10 Matrices):_ **Bachelor in Artificial Intelligence (NEW)**, Data Science, BTI, Computer Engineering, Production Engineering, Business Administration, Managerial Processes, Pedagogy, Mathematics, and Languages.
  - _Applied Logic:_ Automatic real-time calculation of completion percentage, counting of remaining Integrative Projects (PIs), and approval status validation.
- **Hours Bank:** Dynamic tracking of Mandatory Internship hours and Complementary Academic Activities (AACC).

### 🧮 Predictive Calculators

- **Regular Average:** Official institutional algorithm (40% VLE + 60% Exam).
- **Exam Simulator:** Reverse engineering of the formula to discover the exact score needed for direct approval.
- **Make-up Exam Calculation:** Verification of the score needed on the recovery exam (Average 5.0).
- **Weekly Weights:** Weighted average calculator for VLE activities (Dynamic weights: 8%, 12%, and 17%).
- **Integrative Project:** Composite grade estimation (Partial + Final).

### 📅 Information, Dashboards & Guides

- **Critical Deadlines Dashboard:** Real-time countdown timers for VLE closings, Exams, and TCC/PI submissions.
- **2026/2027 Calendar:** Structured schedule with events mapped via JSON-LD `Schedule`.
- **Quick Guides:** Documentation and business rules extracted from the official manual regarding TCC, Mandatory Internship, and Integrative Project.
- **Easy ABNT:** Parametric formatting guide.

---

## 🛠️ Technologies and Dependencies

Project rigorously optimized for **100% Lighthouse** scores (Performance, Accessibility, Best Practices, and SEO).

- **Markup & Style:** `HTML5`, `CSS3` (CSS Variables, Flexbox/Grid, Keyframe Animations).
- **Business Logic:** Pure `JavaScript (ES6+)`, without heavy frameworks to ensure sub-millisecond execution times.
- **Storage:** `localStorage API` (JSON manipulation for persistence of grade arrays and metadata).
- **PWA Ecosystem:** `manifest.json`, `sw.js` (Cache Storage API).
- **UI/UX:** "Mobile-First" Design System, Google Fonts Typography (Inter, Poppins), SVG Icons via [Lucide](https://lucide.dev/).
- **Tracking & Push:** `OneSignalSDK.page.js` and `gtag.js` (Google Tag Manager).

---

## 📂 Directory and File Structure

| File                      | Technical Description                                            |
| :------------------------ | :--------------------------------------------------------------- |
| `index.html`              | Entry point (Main Dashboard) and link hub.                       |
| `progresso.html`          | Curriculum grid engine with JSON DB for 10 matrices.             |
| `calendario.html`         | Interactive schedule optimized for event rich snippets.          |
| `media-final.html`        | Mathematical calculation module for regular grades.              |
| `exame.html`              | School recovery algorithm.                                       |
| `porcentagemsemanas.html` | Interface and logic for weighted average of activities.          |
| `prazo-final...html`      | Dashboard with `setInterval` for countdowns.                     |
| `tcc-pi-estagio.html`     | Documentation of course completion guidelines.                   |
| `main.css` / `style.css`  | Global stylesheets and theme variables.                          |
| `sw.js`                   | Service Worker responsible for offline caching strategies.       |
| `manifest.json`           | Metadata for Progressive Web App installation and configuration. |

---

## ⚠️ Legal Disclaimer and Repository

This is an **UNOFFICIAL** and open-source software.

1.  **No Institutional Link:** The application has no official integration or relationship with the Virtual University of the State of São Paulo (Univesp).
2.  **Database:** The curricular matrices, mathematical weights, and calendars are extracted and hardcoded from public documents (2024/2025/2026), subject to changes by the rectory.
3.  **Information Security:** The code does not intercept, does not travel on the network, and does not collect sensitive academic data (passwords/RAs). All processing occurs `client-side`.

---

<br>

_Frontend Architecture and PWA Project. Focused on workflow optimization and academic UX._
