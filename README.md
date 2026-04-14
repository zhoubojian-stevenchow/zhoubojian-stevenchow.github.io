# Personal Portfolio Website

Job-seeking personal site for **Zhou Bojian (周柏健)** — MSc AI & Business Analytics, Lingnan University Hong Kong.

Live site: **https://zhoubojian-stevenchow.github.io**

## How to deploy (one-time setup)

1. Create a new repository on GitHub named **exactly** `zhoubojian-stevenchow.github.io`
   (the repo name must match your username for a user-level GitHub Pages site).
2. Upload `index.html` to the root of that repo.
3. Go to **Settings → Pages**. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/ (root)**
4. Wait 1–2 minutes, then visit `https://zhoubojian-stevenchow.github.io`.

## Adding your resume PDF

1. Export your CV as `resume.pdf`.
2. Place it in the same folder as `index.html` (repo root).
3. The "Download PDF Resume" button is already wired to `resume.pdf` — no code change needed.

## Editing content

Everything lives in a single `index.html` file. Bilingual content uses `.en` / `.zh` span pairs — edit both when you change any text.

## Tech

- Pure HTML + CSS + vanilla JS (no build step, no dependencies)
- Modern gradient design, fully mobile-responsive
- EN / 中文 language toggle with localStorage persistence
