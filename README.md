# Samuel Ratan — Personal Portfolio Website

A fast, responsive, and accessible personal portfolio website for Samuel Ratan (1st Year Computer Science & Engineering - Data Science).

Built with **HTML5**, **Modern CSS (Custom Properties, Grids, Flexbox)**, and **Vanilla JavaScript** — completely zero-dependency and ready for GitHub Pages hosting.

## 🚀 Features

- **Interactive Planetary Orbit System**:
  - CSS-animated celestial orbits representing Samuel's core pillars: *Code*, *Learning*, *Drawing*, and *Sports / FC Mobile 20★*.
  - Hover / focus tooltips displaying rich information cards for each planet.
  - Orbit slows/pauses when hovered or focused.
  - Interactive legend chips that link directly to each celestial body.
  
- **Dynamic Simulated & Interactive Terminal**:
  - Automated dynamic typing simulation on page load (`whoami`, `status`, `goals`).
  - Fully interactive command prompt: type commands (`help`, `skills`, `fc`, `goals`, `contact`, `clear`) or click quick-action chip buttons.

- **Light & Dark Theme Switcher**:
  - Toggle between dark theme and a clean light theme.
  - FOUC (Flash of Unstyled Content) prevention inline script.
  - Automatically respects user OS system preference (`prefers-color-scheme`) and persists user choices via `localStorage`.

- **Projects & Exploration Lab**:
  - Categorized project cards (*FC Mobile Analyzer*, *DSA Playbook*, *Personal Portfolio*).
  - Interactive category filter tabs (`All`, `Data Science`, `Web & Tools`, `Python`).

- **User Experience & Accessibility**:
  - 1-click **Copy to Clipboard** button with animated toast notification for email.
  - Scroll-spy active navigation highlighting via `IntersectionObserver`.
  - Staggered scroll-reveal entrance animations.
  - Floating back-to-top button.
  - Full support for `prefers-reduced-motion`.

## 💻 Running Locally

Simply open `index.html` in any modern web browser:

```powershell
# In PowerShell:
Start-Process "index.html"
```

Or run a local static server with Python:

```powershell
python -m http.server 8000
# Then visit http://localhost:8000
```
