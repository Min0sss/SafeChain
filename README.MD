# Safe Chain

**Safe Chain** is a visually immersive **Web3 Wallet Landing Page** built with semantic HTML5, advanced SCSS, and Vanilla JavaScript. It demonstrates high-end frontend capabilities including "Glassmorphism" UI design, complex CSS animations, and a robust mobile-first responsive architecture.

This project is a key component of my front-end professional portfolio, showcasing mastery of raw DOM manipulation, modular CSS methodology, and modern aesthetic implementation without relying on heavy frameworks.
---
## Live Demo

https:

## Features

- **Immersive Cyberpunk UI:** 
  - Custom "Glassmorphism" effects using backdrop-filter and translucent gradients.
  - Neon glow effects and dynamic lighting transitions on interactive elements.
- **Modular SCSS Architecture:**
  - Built using the 7-1 Pattern (partials, mixins, variables).
  - Centralized configuration for colors, fonts, and breakpoints for easy maintainability.
- **Advanced Responsive Design:**
  - **Mobile-First Approach:** Styles are optimized for handheld devices first, then scaled up.
  - Custom Breakpoint Mixins (breakpoint-up, breakpoint-down) ensuring pixel-perfect layouts from 360px mobile screens to 4k desktops.
- **Dynamic Interactivity:**
  - Custom **Hamburger Menu** built from scratch with JavaScript toggle logic.
  - Smooth scrolling and sticky navigation header with transparency effects.
- **Visual Motion & Effects:**
  - Infinite Marquee animation for Crypto Tickers (pure CSS).
  - Fade-in entry animations for Hero and Feature sections.
  - Interactive hover states with Z-index manipulation for layered depth.

---

## Tech Stack

* **Core:** HTML5 (Semantic), Vanilla JavaScript (ES6+)
* **Styling:** SCSS / SASS (Advanced Mixins, Nesting, Variables)
* **Architecture:** BEM (Block Element Modifier) Naming Convention
* **Animation:** CSS3 Keyframes & Transitions
* **Icons/Assets:** SVG & Optimized PNGs
* **Deployment:** Vercel
---

## Project Structure

```bash
SAFE-CHAIN/
├─ app/
│  ├─ js/
│  │  └─ script.js
│  └─ scss/
│     ├─ _animations.scss
│     ├─ _articles.scss
│     ├─ _base.scss
│     ├─ _buttons.scss
│     ├─ _features.scss
│     ├─ _footer.scss
│     ├─ _header.scss
│     ├─ _hero.scss
│     ├─ _layout.scss
│     ├─ _marquee.scss
│     ├─ _mixins.scss
│     ├─ _mobile-menu.scss
│     ├─ _typography.scss
│     ├─ _variables.scss
│     └─ style.scss
├─ dist/
│  ├─ style.css
│  └─ style.css.map
├─ images/
│  ├─ logo-min0s.png
│  ├─ menu.svg
│  ├─ x.svg
│  └─ ... (project assets)
├─ index.html
└─ style-guide.md

```
# Clone repository
git clone https://github.com/Min0sss/SafeChain.git

# Navigate to project directory
cd Safe-Chain

# Option A: Open directly
Open index.html in your browser

# Option B: Run with Live Server (VS Code Extension)
Right-click index.html -> "Open with Live Server"

# (Optional) To compile SCSS if you make changes
sass --watch scss/style.scss dist/style.css

##  Notes

- Pure Frontend Power: This project avoids heavy frameworks to demonstrate a deep understanding of the core web technologies (HTML/CSS/JS).

- Performance Focused: Minimal JavaScript overhead; visual effects are hardware-accelerated via CSS transforms and opacity changes.

- CSS Logic: Uses advanced SASS features like calc(), math operations for layout spacing, and custom mixins for managing media queries cleanly.

- No backend or authentication services are connected.

- Cross-Device Compatibility: Rigorously tested on extreme viewports (iPhone SE/Mini to Ultrawide Monitors) to ensure layout stability.

## Author

Guillermo Contreras
Front-End Developer

This project is part of my Professional Portfolio and demonstrates the ability to translate complex UI/UX designs into functional, high-performance code with a focus on visual impact and user experience.