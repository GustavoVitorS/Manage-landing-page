<div align="center">

<img src="docs/manage-landing-page-showcase.png" alt="Manage Landing Page — desktop and mobile project showcase" width="100%">

# Manage Landing Page — PT-BR

**A responsive Frontend Mentor landing page recreated with a Brazilian Portuguese interface.**

[**Live Demo**](https://gustavovitors.github.io/Manage-landing-page/) · [**Source Code**](https://github.com/GustavoVitorS/Manage-landing-page) · [**Frontend Mentor**](https://www.frontendmentor.io/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CD6799?style=flat-square&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-242D52?style=flat-square)

</div>

---

## Overview

**Manage Landing Page** is a front-end implementation of the [Frontend Mentor](https://www.frontendmentor.io/) Manage landing page challenge. The interface has been adapted into **Brazilian Portuguese (PT-BR)** while retaining the project's visual identity and responsive desktop/mobile presentation.

The page introduces a fictional team-productivity platform through a hero section, feature explanations, customer testimonials, calls to action, and a footer newsletter field. This repository contains the front-end demonstration rather than a production service or back-end application.

## Live Preview

- **Live deployment:** [Open Manage Landing Page](https://gustavovitors.github.io/Manage-landing-page/)
- **Repository:** [View source on GitHub](https://github.com/GustavoVitorS/Manage-landing-page)
- **Showcase artwork:** [View full-size preview](docs/manage-landing-page-showcase.png)

The showcase image above is a presentation of the project's existing desktop and mobile layouts; it does not represent a redesign or a feature update.

## Features

- **Responsive page structure** with layouts tailored for mobile and larger viewports.
- **Interactive mobile navigation**, including a hamburger menu and page overlay.
- **Promotional hero section** with illustrations and prominent calls to action.
- **Numbered feature sections** describing the Manage product concept.
- **Testimonial carousel** configured using Swiper.js with navigation and pagination.
- **Scroll-to-top control** implemented with native scrolling and Intersection Observer.
- **Newsletter-style footer input** with an error message triggered by the button. It is not connected to a mailing service, and the existing script does not implement full email-format validation.
- **Brazilian Portuguese copy** throughout the landing page.

## Technologies

| Technology | Purpose |
| --- | --- |
| HTML5 | Semantic page content and sections |
| SCSS / Sass | Source styles, component partials, and responsive media queries |
| CSS3 | Compiled stylesheet consumed by the browser |
| Vanilla JavaScript | Mobile menu, page interactions, scroll-to-top control, and footer feedback |
| Swiper.js | Testimonial slider, navigation, pagination, and autoplay configuration |
| Google Fonts & Font Awesome | Typography and interface icons loaded from external resources |

The project runs as a static website and does not require a JavaScript framework.

## Project Structure

```text
Manage-landing-page/
├── JavaScript/
│   └── main.js                  # Menu, scroll and slider logic
├── images/                     # Logos, illustrations, avatars and icons
├── styles/
│   ├── style.scss               # Sass entry point with partial imports
│   ├── style.css                # Compiled stylesheet used by index.html
│   └── _*.scss                  # Sass partials for page components
├── docs/                       # README-only showcase assets (added)
│   └── manage-landing-page-showcase.png
├── index.html                  # Page entry point
└── README.md                   # English project documentation
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/GustavoVitorS/Manage-landing-page.git
cd Manage-landing-page
```

Open `index.html` in your browser, or serve the folder locally with Python:

```bash
python3 -m http.server 8000
```

Then visit **http://localhost:8000**.

The committed `styles/style.css` is already referenced by `index.html`, so compiling Sass is **not required** just to view the existing version. If you edit SCSS and have Dart Sass installed, you can regenerate the CSS with:

```bash
sass styles/style.scss styles/style.css
```

> **Note:** Some fonts, icons, and the testimonial slider are loaded through external CDNs, so an internet connection may be necessary for the complete appearance and interactions.

## Design and Localization

This implementation follows the original Frontend Mentor challenge and uses the supplied branding and illustrative assets. The page's interface text has been adapted to **PT-BR**. The documentation is intentionally written in **English** to make the repository accessible to a wider developer audience.

## Credits

- **Challenge and design:** [Frontend Mentor](https://www.frontendmentor.io/)
- **Implementation and PT-BR adaptation:** [GustavoVitorS](https://github.com/GustavoVitorS)
- **Carousel library:** [Swiper](https://swiperjs.com/)

---

<div align="center">

**A Frontend Mentor challenge — implemented and localized for Brazilian Portuguese.**

[Back to top](#manage-landing-page--pt-br)

</div>
