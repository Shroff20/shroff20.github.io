# Dr. Sameer Shroff - Portfolio & Technical Services Website

A modern, responsive, high-performance static website for **Dr. Sameer Shroff, Ph.D.**, showcasing technical background, specialized consulting services, computational & engineering projects, and direct contact options.

Built with **pure HTML5, CSS3, and JavaScript** — zero external build steps, zero node dependencies, fast loading, and 100% accessible.

---

## 🌟 Features

- **Semantic HTML5 & Pure CSS Design System**: Clean typography, responsive grid layouts, fluid typography, and modern card designs.
- **Light & Dark Mode Switcher**: Default light theme with seamless theme toggle, local storage persistence, and system preference autodetection (`prefers-color-scheme`).
- **Comprehensive Showcase Sections**:
  - **Hero & Highlights**: High-impact bio, key stats (CMU Ph.D., Bettis Atomic Power Laboratory, 10+ years R&D), and direct calls to action.
  - **Background & Bio**: Detailed narrative of doctoral work at Carnegie Mellon University and mission-critical engineering at Bettis / Naval Nuclear Laboratory.
  - **Interactive Career & Education Timeline**: Visual progression of research, academic degrees, and honors.
  - **Core Skills Matrix**: Scientific computing, FEA / structural dynamics, microscale mechanics/MEMS, and engineering standards.
  - **Projects & Research Portfolio**: Engineering simulations and research in reduced-order modeling, gamified learning, nanoscale contact dynamics, thermal-stress, and biodynamics.
  - **Interactive Deep-Dive Modal**: Modal dialogs with expanded technical methodology, engineering outcomes, and toolchains.
  - **Contact & Inquiry System**: Direct contact info (`sshroff@andrew.cmu.edu`), one-click email copy button with toast notification, and an interactive project inquiry form.
- **Accessible & Fast**: Complete keyboard navigation, ARIA attributes, responsive mobile drawer menu, and zero external build tools required.

---

## 📁 Repository Structure

```
shroff_website_repo/
├── index.html            # Main semantic webpage with all sections and modals
├── css/
│   └── styles.css        # Pure CSS design system, light/dark themes, animations
├── js/
│   └── main.js           # Theme toggle, project filtering, modal dialog, form handler
├── assets/
│   ├── favicon.svg       # Custom branded SVG favicon
│   └── *.mp4, *.png      # Simulation videos and graphics
├── CNAME                 # Custom domain configuration (sameershroff.com)
└── README.md             # Documentation and deployment guide
```

---

## 🚀 How to Run Locally

Because this project is built with pure HTML, CSS, and JS, **no installation or build command is required**.

### Option 1: Direct File Opening
Double-click `index.html` in your file explorer to open it immediately in Chrome, Edge, Safari, or Firefox.

### Option 2: Using Python HTTP Server (Recommended)
Open PowerShell or your terminal in this directory and run:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

### Option 3: VS Code Live Server
Right-click `index.html` inside VS Code and select **"Open with Live Server"**.

---

## 🛠️ How to Customize

- **Updating Contact Information**:
  Search for `sshroff@andrew.cmu.edu` in `index.html` and `js/main.js` to change the email address or add phone/social links.
- **Adding / Modifying Projects**:
  - Edit or add project cards in `index.html` under the `<section id="projects">` container.
  - To update deep-dive modal descriptions, edit the `projectData` object inside `js/main.js`.
- **Styling & Color Palettes**:
  All primary colors, gradients, font families, and card styles are controlled via CSS variables at the top of `css/styles.css`.
