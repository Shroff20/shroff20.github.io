# Dr. Sameer Shroff — Portfolio & Consulting Website

Static personal portfolio and technical consulting website for **Dr. Sameer Shroff, Ph.D.** (`sameershroff.com`), built with **HTML5, CSS3, and vanilla JavaScript** with no build step or package dependencies.

---

## Features

- **Light Mode Default with Dark Mode Toggle**: Defaults to Light Mode with instant `<head>` initialization, manual theme switching, and `localStorage` persistence.
- **Modern Startup & Consulting Design System**: Pure CSS custom properties, `Inter` and `JetBrains Mono` typography (via Google Fonts with system fallbacks), responsive grid layouts, and `prefers-reduced-motion` support.
- **Page Sections**:
  - **Hero (`#hero`)**: Overview, key highlights (`Ph.D.`, `10+ Yrs`, `>$100M`), profile card with expertise chips, and one-click email copy.
  - **Projects (`#projects`)**: 5 project cards with looping `.mp4` simulation/demonstration videos (Reduced-Order Models / PINNs, Gamified Learning, Nanoscale Contact Dynamics, Coupled Multi-Physics Thermal-Stress Assessment, and Biodynamics and Biomechanics).
  - **Background (`#about`)**: Narrative biography and career/education timeline (Naval Nuclear Laboratory / Bettis Atomic Power Laboratory, Carnegie Mellon University Adjunct Professor, and Ph.D. / NSF Research Fellow).
  - **Skills (`#skills`)**: 4 technical competency cards (Scientific Computing & ML, Structural Mechanics & FEA, Materials & Microscale, Engineering Practices).
  - **Contact (`#contact`)**: Direct email (`sshroff@andrew.cmu.edu`) with clipboard copy + toast notification, location/availability info, and a validated inquiry form that drafts an email via `mailto:`.

---

## Repository Structure

```text
shroff_website_repo/
├── .gitignore
├── CNAME                 # Custom domain configuration (sameershroff.com)
├── index.html            # Main webpage
├── README.md             # Project documentation
├── css/
│   └── styles.css        # Design tokens, light/dark themes, and responsive layout
├── js/
│   └── main.js           # Theme toggle, scroll-spy nav, form validation, clipboard/toast
└── assets/
    ├── favicon.svg       # Site icon
    ├── biomech.mp4       # Biodynamics and Biomechanics video
    ├── cavefly_sm.mp4    # Gamified Learning video
    ├── crack.mp4         # Thermal-Stress / Crack Propagation video
    ├── flowmodes2.mp4    # Reduced-Order Models / PINNs video
    ├── slider.mp4        # Nanoscale Contact Dynamics video
    ├── flowmodes.mp4     # Additional media asset
    ├── pend.mp4          # Additional media asset
    ├── fbd.png           # Additional media asset
    └── lqr.svg           # Additional media asset
```

---

## Running Locally

No build or install step is required. Open `index.html` directly in a browser, or serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
