# Agustín Harte — Academic Website (Five Pages)

A responsive, five-page static academic website. All pages use the same `style.css`, `script.js`, and `assets/` folder. No build tools needed.

## Pages
- `index.html` — Home, about, contact
- `research.html` — Current Research
- `journey.html` — Journey
- `publications.html` — Publications & Conferences
- `cv.html` — CV

## Edit
Open the folder in VS Code. Edit the relevant HTML page and save. You can double-click `index.html` or use the Live Server extension to preview. Change fonts/colors in `style.css`. Navigation links are repeated in each HTML file: when adding or renaming a tab, edit the navigation in every page.

**Before publishing:** Replace `YOUR_EMAIL@example.com` and the LinkedIn and Google Scholar placeholders in `index.html`. Verify conference details and update the publication list with actual citations. To enable a downloadable CV: copy your PDF to `assets/Agustin_Harte_CV.pdf`, then in `cv.html` remove the HTML comment markers around the Download CV link and update the “PDF not added yet” text.

## Publish free with GitHub Pages
Create a public repository named `YOURUSERNAME.github.io`. Upload **all contents of this folder** to its root, not the ZIP file or outer folder. In Settings → Pages choose deploy from `main` / root. Your site will be at `https://YOURUSERNAME.github.io/`.

Do not omit `style.css`, `script.js`, or `assets/`, or the website will not look/function correctly.
