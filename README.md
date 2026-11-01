<div align="center">

# ⚡ Trustwave Services

**Digital services, delivered fast and safe.**
Game top-ups, virtual cards, global shopping and more, in one animated single-page site.

![HTML5](https://img.shields.io/badge/HTML5-0a0a0c?style=for-the-badge&logo=html5&logoColor=ffc400)
![CSS3](https://img.shields.io/badge/CSS3-0a0a0c?style=for-the-badge&logo=css3&logoColor=2f6bff)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-0a0a0c?style=for-the-badge&logo=javascript&logoColor=ffc400)
![No dependencies](https://img.shields.io/badge/Dependencies-0-2f6bff?style=for-the-badge)
![RTL](https://img.shields.io/badge/Arabic-RTL-ffc400?style=for-the-badge&labelColor=0a0a0c)

</div>

---

## ✨ Overview

Trustwave Services is a lightweight, Arabic-first (RTL) landing page that presents the services offered and lets customers reach out instantly through WhatsApp.

The whole site lives in **one file**, `index.html`, with no build step, no framework and no external libraries (only a Google Font).

## 🛒 Services

| # | Service | Details |
|---|---------|---------|
| 01 | Game top-ups | Gems and in-game currency in minutes |
| 02 | AliExpress shopping | Order and delivery in 20 to 30 days |
| 03 | Virtual Visa card (Redotpay) | Includes a 5 USD gift |
| 04 | US Google Play account | Points-enabled account |
| 05 | Link-in-bio page development | All your links in a single page |
| 06 | Genshin Impact map clearing | Full map exploration, fast |

## 🎨 Design

- **Palette:** black, yellow, white and blue
- **Look:** bold editorial style with a diagonal corner badge, tilted marquee bands and asymmetric rounded cards
- **Illustrations:** custom inline SVG artwork for each service, no external images
- **Motion:** animated background glow and particles, scroll reveal, 3D card tilt, shimmering buttons, scroll progress bar
- **Accessibility:** animations switch off automatically for visitors who enable *reduce motion*
- **Responsive:** built mobile-first, from phones to wide desktops

## 📁 Structure

```
.
├── index.html   # the entire site: HTML + CSS + JS
└── README.md
```

Inside `index.html` the code is split into clearly commented sections:

| Section | What it contains |
|---------|------------------|
| 1. Variables | Colors, font, spacing and radii in one place |
| 2 to 9. Components | Base styles, buttons, nav, hero, services, FAQ, footer, reveal effects |
| 10. Life | Background, marquee, tilt, SVG animations |
| Markup | NAV, HERO, TICKER, SERVICES, FAQ, FOOTER |
| Script | Counter, marquee builder, scroll effects, particles |

## 🛠️ Customize

**Change colors or fonts**
Edit the variables at the top of the `<style>` block:

```css
:root{
  --yellow: #ffc400;
  --blue:   #2f6bff;
  --black:  #0a0a0c;
  --font:   "Tajawal", system-ui, sans-serif;
}
```

**Add a service**
Copy any `<article class="card reveal">` block inside `#services`, then change its title, description and illustration. Numbering, the counter in the hero corner and the marquee text all update automatically.

**Use a photo instead of an illustration**
Replace the `<svg>` inside `card__media` with:

```html
<img src="your-image-url" alt="Service name" loading="lazy">
```

**Change the contact link**
Search for `wa.me` in `index.html` and replace the WhatsApp link (it appears in the nav and the footer).

**Tone the animation down**
Look at section 10 of the CSS: `.ticker__track` controls marquee speed, and the particle count is set near the end of the script.

## 🚀 Deploy on GitHub Pages

1. Push `index.html` to the root of your repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then pick `main` and `/ (root)`.
4. Save, and your site goes live in a minute or two.

## 📬 Contact

Orders and questions go through WhatsApp: [**Message us**](https://wa.me/qr/FV7SEVGKI5HVJ1)

---

<div align="center">

Made with 💛 by **KIRA** · © 2024 All rights reserved

</div>
