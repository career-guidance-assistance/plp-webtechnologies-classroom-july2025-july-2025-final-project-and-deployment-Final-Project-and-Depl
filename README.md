# GLORIA — AI Software Engineer — Portfolio

Professional static portfolio website for Gloria Ngwu, an AI Software Engineer focused on building production-ready machine learning systems. This repository contains the source for a one-page portfolio (HTML, CSS, JS) plus a resume page and assets.

Live demo/ Deployment link

- https://career-guidance-assistance.github.io/plp-webtechnologies-classroom-july2025-july-2025-final-project-and-deployment-Final-Project-and-Depl/

Quick overview

- Purpose: Showcase Gloria's skills, projects, and contact info. The site is intentionally lightweight and suitable for static hosting (GitHub Pages, Netlify, Vercel).
- Tech: Plain HTML, CSS and vanilla JavaScript.

Repository structure

Root files and important folders:

- `index.html` — Main portfolio page (one-page layout: hero, about, services, skills, projects, contact).
- `resume.html` — Standalone resume page (print-friendly).
- `GLORIA CHIDIMA NGWU, AL SOFTWARE ENGINEER CV.pdf` — Resume PDF for download/viewing.
- `style.css` — Primary site stylesheet.
- `main.js` — Main JavaScript entry (site interactions: modal, smooth scroll, form behaviour).
- `animations.css`, `styles.css` — Additional CSS used by the project.
- `animations.js`, `theme.js` — Additional JavaScript.
- `images/` — Image assets used on the site (hero, profile, project screenshots).

How to preview locally

Because this is a static site you can preview it by opening `index.html` in your browser. For a more accurate local test and to avoid file:// limitations, run a small HTTP server.

Using Python 3 (PowerShell):

```powershell
# Serve current folder at http://localhost:5500
python -m http.server 5500
```

Using Node (http-server):

```powershell
npm install -g http-server
http-server -p 5500
```

Then open http://localhost:5500 in your browser.

Notes and recommendations

- Resume links: The About section and footer include links to view or download the resume PDF (`GLORIA CHIDIMA NGWU, AL SOFTWARE ENGINEER CV.pdf`) and to open `resume.html`.
- Contact form: The contact form is static and will not send emails out of the box. To enable contact submissions, integrate a form backend (Formspree, Netlify Forms) or a server endpoint.
- CSS/JS consolidation: The project contains a few CSS/JS files. If you prefer a single CSS and JS bundle, I can consolidate them and update `index.html` accordingly.
- Accessibility: The site uses semantic HTML and some ARIA roles; consider running an accessibility audit (Lighthouse) and adding skip links and additional form labels if desired.

Contributing

- Create an issue for bugs or feature requests.
- For small changes, open a PR targeting the `main` branch.

License & attribution

- This repository contains original work for a portfolio. Add an appropriate license file if you intend to publish or share widely.

Contact

- GitHub: https://github.com/chibeauty
- Email: gloriangwu45@gmail.com

---

If you'd like, I can also:

- Add a `package.json` with a `start` script for the local server.
- Consolidate and minify CSS/JS files.
- Add a small deployment section (GitHub Pages or Netlify steps) to the README.

