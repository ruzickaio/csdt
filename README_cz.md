# CSDT Portfolio — Cascade Scroll-Driven Triggers UI Template

CSDT (Cascade Scroll-Driven Triggers) je pokročilý, animovaný webový framework nebo spíše static aio-template zaměřený na moderní design, výkon a plynulý uživatelský zážitek. Využívá knihovnu [GSAP](https://greensock.com/gsap/) (včetně ScrollTrigger) pro scrollované animace a nabízí responzivní prezentaci obsahu.

> Není potřeba žádná buildovací pipeline – vše funguje čistě v HTML/CSS/JS (client-side only).


##  Funkce

- **Scroll-Driven Animace** – kaskádové animace sekcí podle scrollu.
- **Moderní UI Design** – custom CSS proměnné, gradienty, stíny, glassmorphism.
- **Sekce Dovedností a Projektů** – vizuální zobrazení schopností a portfolia.
- **Scroll indikátory** – navigační body pro rychlý přechod mezi sekcemi.
- **Plně responzivní** – optimalizace pro všechna zařízení.
- **Fallback režim** – IntersectionObserver při nedostupnosti GSAP.

## 📂 Struktura

Projekt je v jediném HTML souboru `csdt-portfolio-fixed3.html`:

- Kompletní HTML struktura
- Inline CSS (včetně animací)
- Inline JavaScript s třídou `CSDTSystem` pro interakce a animace

## 🛠️ Technologie

| Technologie                | Použití                               |
| -------------------------- | ------------------------------------- |
| HTML5                      | Struktura layoutu                     |
| CSS3                       | Stylování a animace                   |
| GSAP                       | Animace a scroll interakce            |
| ScrollTrigger              | Synchronizace animací se scrollováním |
| Font Awesome               | Ikony v UI                            |
| Comfortaa & JetBrains Mono | Typografie                            |

## 🧠 Architektura JavaScriptu

Veškerá logika je ve třídě `CSDTSystem`:

- `checkGSAPLoaded()` – detekce GSAP/ScrollTrigger
- `initGSAPAnimations()` – kaskádové animace sekcí
- `initFallbackAnimations()` – IntersectionObserver fallback
- `initProgressBar()` – dynamický scroll progress
- `initIndicators()` – interaktivní navigační body
- `initSmoothScrolling()` – plynulé scrollování

## 🔒 Bez backendu

Projekt je **statický** – vhodný pro GitHub Pages, Vercel, Netlify nebo vlastní CDN.

## 📫 Kontakt

Autor: [Jakub Růžička](https://ruzickajakub.cz)  
Email: [csdt@vics.cz](mailto:csdt@vics.cz)  
GitHub: [@csdt](https://github.com/ruzickaio/csdt)

## 📄 Licence

MIT License – free to use, modify and distribute.

---

> “Let your scroll tell a story. CSDT animates with intention.”
# 🌐 CSDT Portfolio — Cascade Scroll-Driven Triggers UI System

CSDT (Cascade Scroll-Driven Triggers) je pokročilý, animovaný webový framework nebo spíše static aio-template zaměřený na moderní design, výkon a plynulý uživatelský zážitek. Využívá knihovnu [GSAP](https://greensock.com/gsap/) (včetně ScrollTrigger) pro scrollované animace a nabízí responzivní prezentaci obsahu.

> Není potřeba žádná buildovací pipeline – vše funguje čistě v HTML/CSS/JS (client-side only).


##  Funkce

- **Scroll-Driven Animace** – kaskádové animace sekcí podle scrollu.
- **Moderní UI Design** – custom CSS proměnné, gradienty, stíny, glassmorphism.
- **Sekce Dovedností a Projektů** – vizuální zobrazení schopností a portfolia.
- **Scroll indikátory** – navigační body pro rychlý přechod mezi sekcemi.
- **Plně responzivní** – optimalizace pro všechna zařízení.
- **Fallback režim** – IntersectionObserver při nedostupnosti GSAP.

## 📂 Struktura

Projekt je v jediném HTML souboru `csdt-portfolio-fixed3.html`:

- Kompletní HTML struktura
- Inline CSS (včetně animací)
- Inline JavaScript s třídou `CSDTSystem` pro interakce a animace

## 🛠️ Technologie

| Technologie                | Použití                               |
| -------------------------- | ------------------------------------- |
| HTML5                      | Struktura layoutu                     |
| CSS3                       | Stylování a animace                   |
| GSAP                       | Animace a scroll interakce            |
| ScrollTrigger              | Synchronizace animací se scrollováním |
| Font Awesome               | Ikony v UI                            |
| Comfortaa & JetBrains Mono | Typografie                            |

## 🧠 Architektura JavaScriptu

Veškerá logika je ve třídě `CSDTSystem`:

- `checkGSAPLoaded()` – detekce GSAP/ScrollTrigger
- `initGSAPAnimations()` – kaskádové animace sekcí
- `initFallbackAnimations()` – IntersectionObserver fallback
- `initProgressBar()` – dynamický scroll progress
- `initIndicators()` – interaktivní navigační body
- `initSmoothScrolling()` – plynulé scrollování

## 🔒 Bez backendu

Projekt je **statický** – vhodný pro GitHub Pages, Vercel, Netlify nebo vlastní CDN.

## 📫 Kontakt

Autor: [Jakub Růžička](https://ruzickajakub.cz)  
Email: [csdt@vics.cz](mailto:csdt@vics.cz)  
GitHub: [@csdt](https://github.com/csdt)

## 📄 Licence

MIT License – free to use, modify and distribute.

---

> “Let your scroll tell a story. CSDT animates with intention.”
