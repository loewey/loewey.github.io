# Personal Website

A clean, academic personal website built with plain HTML, CSS, and JavaScript. Designed for GitHub Pages hosting with zero build step.

## Quick Start

1. **Edit your content** in `index.html` — update name, bio, email, links, research, projects, and publications.
2. **Add your photo** — replace the placeholder `<div>` in the hero section with `<img src="photo.jpg" alt="Your Name">` and place your photo file in the root directory.
3. **Push to GitHub** and enable GitHub Pages.

## Deploying to GitHub Pages

### Option A: User/Organization site (`username.github.io`)

1. Rename this repository to `<your-github-username>.github.io`
2. Push to the `main` branch
3. Go to **Settings → Pages → Source** and select `Deploy from a branch` → `main` → `/ (root)`
4. Your site will be live at `https://<your-github-username>.github.io/`

### Option B: Project site (`username.github.io/repo-name`)

1. Push to the `main` branch
2. Go to **Settings → Pages → Source** and select `Deploy from a branch` → `main` → `/ (root)`
3. Your site will be live at `https://<your-github-username>.github.io/Personal-website/`

## File Structure

```
├── index.html    # Main page with all content
├── style.css     # All styles
├── script.js     # Navigation interactivity
└── README.md     # This file
```

## Customization

- **Colors**: Edit CSS custom properties and color values in `style.css`
- **Sections**: Add/remove sections in `index.html`
- **Font**: Change the Google Fonts import in `index.html` `<head>`
- **Photo**: Drop a `photo.jpg` in the root and update the HTML
