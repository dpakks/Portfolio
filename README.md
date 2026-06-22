# Deepak Kumar — Portfolio

A terminal / infrastructure themed personal portfolio. Built as a fast, dependency light static site: a sidebar file tree, a typed config card, an interactive console you can actually type into, and a resizable terminal dock.

Focus areas: Software Engineering, Cloud, DevOps, and AI (RAG and Gen AI).

## Features

- Terminal styled UI with a sidebar "file tree" and `.tf` style section names
- Interactive console (type `help`) with commands like `about`, `skills`, `experience`, `projects`, `resume`
- Resizable, VS Code style terminal dock — drag the top edge to resize, double click to reset
- Animated section reveals and an ambient canvas background
- Pixel art avatar, downloadable resume, fully responsive

## Sections

- **Home** — intro and a config style summary card
- **About** — background and what I build
- **Skills** — tech stack across Cloud, Backend, Frontend, DevOps, and Data
- **Experience** — roles at Prodex Technologies and HealthOneCloud
- **Projects** — featured work: cloud infrastructure, AI tooling, and web apps
- **Contact** — links and ways to reach me

## Built With

- **HTML, CSS, and vanilla JavaScript** — no framework, no build step, no bundler
- **Iconify** — tech stack icons (loaded from CDN)
- **Google Fonts** — Orbitron, Fira Code, Space Grotesk

There are no dependencies to install. Everything is plain static files.

## Project Structure

```
index.html          all markup + inline JavaScript
style.css           all styling
avatar_preview.png  pixel art avatar (also used as the favicon)
src/pdf/            resume PDF
README.md
```

## Run Locally

1. Open the folder in VS Code.
2. Open `index.html` in a browser, or use the **Live Server** extension for hot reload.

## Deploy

It is a static site, so any static host works — Netlify, Vercel, GitHub Pages, or AWS S3 + CloudFront. Upload the files (keep the `src/` folder so the resume link resolves) and point the host at `index.html`.

---

*"Automate. Deploy. Repeat."*
