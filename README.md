# Kunal Singh — Personal Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black)

A premium, single-file personal portfolio website built for **Kunal Singh**, a B.Tech Computer Science (AI/ML) student at RV University, Bengaluru. Designed with a motion-driven, dark aesthetic featuring a **Black & Emerald Green** color theme, cinematic splash screen, and interactive 3D background.

---

## ✨ Features

### 🎬 Cinematic Splash Screen
- **Two-stage loading sequence** on every page load/refresh
- **Stage 1 — Identity:** "KUNAL SINGH" fades and scales in at the exact viewport center, rendered in **Archivo Black** with a white-to-emerald gradient and wide tracking
- **Stage 2 — Vertical Split:** The screen splits into top and bottom halves that slide apart, revealing the Hero section behind them using premium `cubic-bezier(0.77, 0, 0.175, 1)` easing (800–1000ms duration)
- Overlay elements are **removed from the DOM** after completion to ensure full interactivity

### 🌐 Interactive 3D Background
- Built with **Three.js (r134)** — 250 floating emerald-green particles rendered via `THREE.Points` and `AdditiveBlending` for a glowing depth effect
- Gentle autonomous drift animation with **mouse parallax** response
- Runs on a fixed `z-index: -1` canvas for zero layout interference

### 🎨 Design System
| Token | Value |
|---|---|
| Background | `#0A0F1A` (deep slate-black) |
| Surface | `#111827` (gray-900) |
| Accent | `#10B981` (emerald) |
| Gold | `#F59E0B` (amber) |
| Titles | `#F1F5F9` (slate-100) |
| Subtexts | `#94A3B8` (slate-400) |
| Display Font | **Space Grotesk** |
| Body Font | **Inter** |
| Splash Font | **Archivo Black** |

### 🖼️ Sections
| Section | Description |
|---|---|
| **Hero** | Avatar, KUNAL SINGH heading, typewriter role cycling, Resume / GitHub / LinkedIn CTAs |
| **About** | Bio, stat pills: CGPA · 5+ Projects · RV University |
| **Skills** | Categorized pill badges — Languages, Frameworks, Tools, Soft Skills |
| **Projects** | 4 featured projects: Snake Game, Student Performance Predictor, RoadLens, Portfolio |
| **Certifications** | 3 verifiable certificates with direct Google Drive links |
| **Contact** | Email, GitHub, and LinkedIn cards with arrow-link hover effects |

### ⚡ Animations & Interactions
- **GSAP + ScrollTrigger** — Coordinated scroll-reveal animations (fade-up, slide-in) for every section
- **Typewriter Effect** — Cycles through role phrases with character-by-character rendering and blinking caret
- **Vanilla-Tilt.js** — Subtle 3D perspective tilt on glass cards
- **Micro-animations** — Skill badge hover fills, project icon glow pulses, contact card arrow transitions
- **Theme Toggle** — Light/Dark mode with persistent `localStorage` state

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 (single file) |
| Styling | Tailwind CSS (CDN JIT) + Vanilla CSS |
| 3D Graphics | Three.js r134 |
| Animations | GSAP 3.12.2 + ScrollTrigger |
| Tilt Effect | Vanilla-Tilt 1.8.0 |
| Icons | FontAwesome 6.4.0 |
| Fonts | Google Fonts — Archivo, Space Grotesk, Inter |

---

## 📂 File Structure

```text
portfolio/
├── index.html    # All HTML, Tailwind config, CSS, and JS in one file
└── hero-bg.png   # Legacy background asset (unused in current build)
```

---

## 🚀 Running Locally

No build step required. Open with any static file server:

```bash
# VS Code Live Server extension — just click "Go Live"
# or
npx serve .
```

---

## 📌 Projects Featured

| # | Project | Stack |
|---|---|---|
| 1 | **Snake Game** | Java, Swing, AWT |
| 2 | **Student Performance Predictor** | Python, ML, RandomForest, LLaMA |
| 3 | **RoadLens — Traffic Sign Recognition** | Python, CNN, OpenCV, TensorFlow |
| 4 | **Personal Portfolio Website** | HTML/CSS, JS, Three.js, GSAP |

---

© 2026 Kunal Singh
