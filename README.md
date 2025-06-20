# Kingsukh Guest House – Website Redesign

> **A modern, responsive, and SEO‑friendly revamp of the official Kingsukh Guest House website, built as my final project during the Web Development Internship at Innobyte Services.**

---

## Table of Contents
1. [About](#about)
2. [Live Demo](#live-demo)
3. [Features](#features)
4. [Tech Stack](#tech-stack)
5. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation & Run Locally](#installation--run-locally)
6. [Project Structure](#project-structure)
7. [Contributing](#contributing)
8. [Roadmap](#roadmap)
9. [License](#license)
10. [Contact](#contact)

---

## About
This project redesigns the legacy site of **Kingsukh Guest House** (Purulia, West Bengal) to improve usability, aesthetics, and performance while preserving its brand identity. The deliverable meets real‑world business requirements gathered from the property owner and Innobyte’s design brief.

## Live Demo
| Environment | Link |
|-------------|------|
| **Production** | <https://kingsukhguesthouse.com> *(original)* |
| **Redesigned Preview** | <https://muditgupta07.github.io/Innobyte-Services-Intern-Project/> *(GitHub Pages)* |

> **Tip:** If the preview is offline, clone the repo and follow the _Getting Started_ section below.

## Features
- ✨ **Hero section** with full‑width background, gradient overlay, & call‑to‑action.
- 📱 **Responsive navigation** that blurs & solidifies on scroll; collapses into a slide‑down mobile menu.
- 🏠 **Informative sections**: About, Gallery, Rooms, Services, Contact.
- 🌊 **Wave SVG dividers** for smooth visual flow between sections.
- 🎞️ **AOS‑powered scroll animations** for subtle interactivity.
- 💬 **WhatsApp "Book Now" buttons** (deep link: `wa.link/at5ion`).
- 🗺️ Embedded **Google Maps** and pre‑filled **tel/mail links**.
- 🔍 **SEO & accessibility** best practices (meta tags, semantic HTML, high‑contrast palette & `alt` text).

## Tech Stack
| Layer | Technology |
|-------|------------|
| Mark‑up | **HTML5** (semantic) |
| Styling | **Tailwind CSS** CDN (utility‑first) |
| Icons | **Remix Icons** |
| Animations | **AOS v2.3.1** |
| Tooling | Vanilla JS, VS Code + Live Server, Git/GitHub |

_No build step is required – everything is delivered via CDN._

## Getting Started
### Prerequisites
- **Git** ≥ 2.20
- Any modern web browser (Chrome, Edge, Firefox, Safari…)
- Optional: **VS Code** with the _Live Server_ extension for hot‑reload.

### Installation & Run Locally
```bash
# 1. Clone the repository
$ git clone https://github.com/MuditGupta07/Innobyte-Services-Intern-Project.git
$ cd Innobyte-Services-Intern-Project

# 2. Option A – Double‑click index.html
#    Works instantly if you just need a quick preview.

# 3. Option B – Via VS Code Live Server (recommended)
#    a) Open the project folder in VS Code
#    b) Right‑click index.html ▸ "Open with Live Server"

# 4. Option C – Serve with Python (no extensions required)
$ python -m http.server 9000
# Then navigate to http://localhost:9000 in your browser.
```

## Project Structure
```text
├── assets/               # Images & favicon
│   ├── baranti.webp
│   ├── out.jpg
│   └── ...
├── index.html            # Main entry point
└── README.md             # Project documentation (you’re here)
```
> **Note:** All third‑party libraries are CDN‑hosted, so no `node_modules` or package JSON is required.

## Contributing
Contributions are welcome! To propose an improvement:
1. Fork this repo & create a feature branch: `git checkout -b feat/your‑feature`  
2. Commit your changes with clear messages.
3. Push to your fork & open a **pull request** describing _why_ the change is valuable.

## Roadmap
- [ ] Hook the **contact form** to FormSubmit / Netlify Forms.
- [ ] Replace placeholder social links with real profiles once confirmed.
- [ ] Add Lighthouse CI to keep performance & a11y scores ≥ 90.
- [ ] Convert inline Tailwind config to **JIT build pipeline** for production (optional).

## License
Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

## Contact
**Mudit Gupta** – muditg782005@gmail.com  
GitHub: <https://github.com/MuditGupta07>  
LinkedIn: <https://www.linkedin.com/in/mudit-gupta-249677294/>

> _Built with ❤️ & ☕ during the Innobyte Services Web Development Internship._
