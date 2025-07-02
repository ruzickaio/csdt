# CSDT Portfolio — Cascade Scroll-Driven Triggers UI Template

CSDT (Cascade Scroll-Driven Triggers) is an advanced, animated web framework—or rather, a static aio-template focused on modern design, performance, and a smooth user experience. It leverages the [GSAP](https://greensock.com/gsap/) library (including ScrollTrigger) for scroll-based animations and offers a responsive content presentation.

> No build pipeline required – everything works purely in HTML/CSS/JS (client-side only).

##  Features

- **Scroll-Driven Animations** – cascading section animations based on scroll.
- **Modern UI Design** – custom CSS variables, gradients, shadows, glassmorphism.
- **Skills & Projects Sections** – visual display of skills and portfolio.
- **Scroll Indicators** – navigation dots for quick section jumps.
- **Fully Responsive** – optimized for all devices.
- **Fallback Mode** – IntersectionObserver if GSAP is unavailable.

## 📂 Structure

The project is a single HTML file: `csdt-portfolio-fixed3.html`:

- Complete HTML structure
- Inline CSS (including animations)
- Inline JavaScript with the `CSDTSystem` class for interactions and animations

## 🛠️ Technologies

| Technology                | Purpose                                |
| ------------------------- | -------------------------------------- |
| HTML5                     | Layout structure                       |
| CSS3                      | Styling and animations                 |
| GSAP                      | Animations and scroll interactions     |
| ScrollTrigger             | Syncing animations with scrolling      |
| Font Awesome              | UI icons                               |
| Comfortaa & JetBrains Mono| Typography                             |

## 🧠 JavaScript Architecture

All logic is encapsulated in the `CSDTSystem` class:

- `checkGSAPLoaded()` – detects GSAP/ScrollTrigger
- `initGSAPAnimations()` – cascading section animations
- `initFallbackAnimations()` – IntersectionObserver fallback
- `initProgressBar()` – dynamic scroll progress
- `initIndicators()` – interactive navigation dots
- `initSmoothScrolling()` – smooth scrolling

## 🔒 No Backend

The project is **static** – suitable for GitHub Pages, Vercel, Netlify, or your own CDN.

## 📫 Contact

Author: [Jakub Růžička](https://ruzickajakub.cz)  
Email: [csdt@vics.cz](mailto:csdt@vics.cz)  
GitHub: [@csdt](https://github.com/ruzickaio/csdt)

## 📄 License

MIT License – free to use, modify and distribute.

---

> “Let your scroll tell a story. CSDT animates with intention.”
