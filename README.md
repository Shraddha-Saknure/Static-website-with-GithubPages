# 3D Coverflow Website

A responsive, interactive image gallery built with HTML, CSS, and JavaScript. The project was created for Elevate Labs DevOps Internship Task 6 and is published with GitHub Pages.

## TASK 5: Host a Static Website with GitHub Pages

**Objective:** Deploy a simple HTML website using GitHub Pages.

**Tools:** GitHub Pages

**Deliverables:** [Live website](https://shraddha-saknure.github.io/Static-website-with-GithubPages/) and [GitHub repository](https://github.com/Shraddha-Saknure/Static-website-with-GithubPages)

### Mini guide

1. Create an `index.html` file for the website.
2. Push it to a new GitHub repository.
3. Open the repository's **Settings → Pages** and enable GitHub Pages.
4. For branch-based publishing, select the `main` branch and `/(root)` folder. This repository uses the GitHub Actions publishing option instead; its workflow deploys the repository root on every push to `main`.
5. Open the live website using the link above.
6. Customize the site with CSS and push your changes.

## GitHub Pages

Site URL: [3D Coverflow Website](https://shraddha-saknure.github.io/Static-website-with-GithubPages/)

## Features

- Interactive 3D coverflow gallery with seven landscape images
- Previous/next controls, slide indicators, and autoplay
- Responsive layout with touch and keyboard navigation
- About and contact sections

## Project files

- `index.html` — page structure and gallery image references
- `templatemo-3d-coverflow.css` — layout, styling, and animations
- `templatemo-3d-coverflow-scripts.js` — gallery interactions
- `images/` — image assets used in the gallery

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

## GitHub Pages deployment

GitHub Pages is configured to publish through **GitHub Actions**. The `Deploy website to GitHub Pages` workflow deploys the repository root whenever changes are pushed to `main`; it also supports manual runs from the **Actions** tab.

## Credits

The 3D Coverflow template is by [TemplateMo](https://templatemo.com/). See the template attribution in `index.html`.
