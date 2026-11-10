# 🎯 Goal Classifier

> **A minimalist, wireframe-inspired workspace for clarifying goals, designing execution plans, and diagnosing execution readiness.**

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-18181b?style=for-the-badge&logo=github&logoColor=white)](https://alimkhalelov.github.io/goal-classifier/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Web Crypto](https://img.shields.io/badge/Security-Web_Crypto_API-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## ⚡ Overview

**Goal Classifier** is a fast, distraction-free goal setting and planning interface. It organizes objectives across four vital dimensions:
1. **Goal Statement:** Clear definition of intent.
2. **Deadline & Time Horizons:** Precise time bounding and remaining day indicators.
3. **Execution Plan:** Breakdowns into concrete sub-actions and tasks.
4. **Regularity:** Daily/weekly habits and routines necessary to sustain momentum.
5. **Diagnosis:** Instant heuristic feedback on goal viability and structure.

---

## 🕹️ Key Features

- **Editorial Minimalist Aesthetic:** Carefully crafted typography using *Instrument Serif*, *Plus Jakarta Sans*, and *Space Mono* with subtle wireframe inputs.
- **Dynamic Heuristic Diagnosis:** Evaluates the balance between deadlines, sub-plans, and regular habits in real time.
- **Client-Side Persistence:** Automatically saves your goals and progress to browser `localStorage` (`wireframe_goal_classifier_en_v2`).
- **Encrypted BYOK AI Diagnostics:** Optional Bring-Your-Own-Key support for Gemini, OpenAI, and Anthropic. API keys are encrypted client-side using the native browser **Web Crypto API** (AES-GCM) and never touch any third-party server.
- **Zero-Build Architecture:** Completely self-contained single-page application requiring no build steps, bundlers, or server runtimes.

---

## 🚀 Quick Start

### Option 1: Live Web App
Open directly in your browser:  
👉 **[alimkhalelov.github.io/goal-classifier](https://alimkhalelov.github.io/goal-classifier/)**

### Option 2: Run Locally

Clone the repository and open `index.html` in any browser:

```bash
git clone https://github.com/alimkhalelov/goal-classifier.git
cd goal-classifier

# Simply open the file:
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve with Python or any local HTTP server:

```bash
python -m http.server 8000
# Navigate to http://localhost:8000
```

---

## 🛰️ Deployment

Continuous Deployment to **GitHub Pages** is fully automated via GitHub Actions (`.github/workflows/deploy.yml`):
- Pushes to the `main` branch trigger an automatic build-less artifact upload.
- Deployed seamlessly to GitHub Pages.

---

## 📜 License

MIT © [Alimzhan Khalelov](https://github.com/alimkhalelov)
