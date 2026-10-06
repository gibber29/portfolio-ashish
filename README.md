# Ashish Choudhary — Portfolio

A responsive personal portfolio showcasing AI systems, backend engineering, systems programming, internship experience, skills, and achievements.

## Run locally

No build step or package installation is needed. With Python installed, run:

```bash
python -m http.server 8000 --directory dist
```

Open `http://localhost:8000` in your browser.

## Project structure

- `dist/index.html` — page content, project panels, skills, and achievements
- `dist/style.css` — responsive layouts, theme, and visual effects
- `dist/script.js` — project filters, interactive diagrams, animations, and email copying
- `dist/assets/` — optimized WebP hero artwork and doodle illustrations
- `dist/resume.pdf` — downloadable resume

## Features

- Dark editorial design with cream and lime accents
- Scroll reveals, parallax, subtle card tilt, and hover effects
- Filterable project showcase and interactive RAG explanation
- Expandable skill groups and achievement cards
- Keyboard navigation and reduced-motion support
- Responsive desktop and mobile layouts

## Editing

Edit the files in `dist/` directly. Keep relative asset paths intact and replace `dist/resume.pdf` when updating the resume. Fonts load from Google Fonts, with local system fallbacks.

The site is plain HTML, CSS, and JavaScript. It does not require React, a backend, environment variables, or API keys. It can be served by any static host using `dist/` as the published directory.

The generated artwork is included with the project. Project links lead to their respective repositories and deployments. The contact button opens the visitor's email application; it does not use a form backend.
