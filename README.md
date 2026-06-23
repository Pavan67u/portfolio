# Pavan Chary — Portfolio

Personal portfolio website. Built with HTML5, CSS3, Vanilla JS. No dependencies. GitHub Pages ready.

## Quick Deploy

### GitHub Pages (recommended)

1. Create repo: `pavan67u.github.io` (use your GitHub username exactly)
2. Push all files to `main` branch
3. Go to **Settings → Pages → Source → main branch → / (root)**
4. Live at `https://pavan67u.github.io` in ~2 minutes

```bash
git init
git add .
git commit -m "init: portfolio"
git remote add origin https://github.com/Pavan67u/pavan67u.github.io.git
git push -u origin main
```

### Any static host (Netlify, Vercel, Cloudflare Pages)
Drop the folder — works out of the box.

## File Structure

```
portfolio/
├── index.html          # Main page
├── assets/
│   ├── css/style.css   # All styles + dark/light theme
│   ├── js/main.js      # Theme, typing, filter, scroll
│   └── images/         # Add profile photo here
├── README.md
├── sitemap.xml
└── robots.txt
```

## Customisation

### Add your profile photo
1. Save as `assets/images/avatar.jpg`
2. In `index.html`, replace the hero visual section with an `<img>` tag

### Add your resume PDF
1. Save as `assets/resume.pdf`
2. The download button already points to this path

### Update links
All social links, email, and GitHub URL are in `index.html`. Search for `Pavan67u` or `charypavan685` to find them.

### Config file (quick edits)
Open `index.html` and edit the `<head>` meta section for SEO title/description.

## Features

- Dark / Light mode (persisted in localStorage)
- Typing animation in hero
- Scroll reveal animations
- Project filter (All / AI-ML / Full-Stack / Backend)
- Mobile navigation
- Contact form (opens mail client)
- Back-to-top button
- ATS-friendly content
- SEO meta + Open Graph + JSON-LD

## Lighthouse

Expected scores: Performance 95+, Accessibility 90+, Best Practices 95+, SEO 100.
No external JS dependencies. Single CSS file. Lazy-load ready.

---
Built by Auvsula Pavan Chary · 2026
