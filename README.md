# Siddhant Kasture — Portfolio

Personal portfolio website built for GitHub Pages.

## 🚀 Quick Start

1. Create a new GitHub repository named `sid12super.github.io` (or any repo name)
2. Push this code to the `main` branch
3. Go to **Settings → Pages → Source** and select `main` branch
4. Your site will be live at `https://sid12super.github.io/`

## 📁 Structure

```
├── index.html          # Main portfolio page (Home + About)
├── README.md           # This file
└── assets/             # Future: images, resume PDF, etc.
```

## ✏️ How to Edit

Everything is in a single `index.html` file for simplicity. Here's where to find each section:

| Section | What to edit |
|---------|-------------|
| **Hero** | Search for `<!-- HERO -->` — update tagline, subtitle |
| **About** | Search for `<!-- ABOUT -->` — update bio paragraphs, stats |
| **Experience** | Search for `<!-- EXPERIENCE -->` — add/edit job entries |
| **Projects** | Search for `<!-- PROJECTS -->` — add project cards with GitHub links |
| **Skills** | Search for `<!-- SKILLS -->` — update skill tags |
| **Education** | Search for `<!-- EDUCATION -->` — update degree info |
| **Contact** | Search for `<!-- CONTACT -->` — update email, phone, links |

### Adding a New Project

Copy an existing `<a class="project-item">` block and update the content:

```html
<a href="YOUR_GITHUB_LINK" target="_blank" rel="noopener" class="project-item reveal">
  <span class="project-num">05</span>
  <div class="project-info">
    <h3>Project Title</h3>
    <p>Brief description</p>
  </div>
  <div class="project-tech">
    <span>Tech1</span>
    <span>Tech2</span>
  </div>
  <span class="project-arrow">→</span>
</a>
```

### Adding a New Experience Entry

Copy an existing `.exp-item` block:

```html
<div class="exp-item reveal">
  <div class="exp-date">Start — End</div>
  <div class="exp-content">
    <h3>Role Title</h3>
    <div class="company">Company · Location</div>
    <p>Description of your work.</p>
  </div>
</div>
```

## 🎨 Customization

### Colors
Edit CSS variables at the top of `index.html`:

```css
:root {
  --bg: #0a0a0b;           /* Background */
  --accent: #FFD600;        /* Primary accent (yellow) */
  --highlight: #e0ff00;     /* Secondary accent */
  --text-primary: #f0efe9;  /* Main text */
}
```

### Fonts
Currently using Google Fonts: **Syne** (display), **Outfit** (body), **JetBrains Mono** (code).

## 📄 Future Pages

To add more pages (e.g., a dedicated Projects page):
1. Create a new `.html` file (e.g., `projects.html`)
2. Update nav links in `index.html`
3. Copy the nav, footer, and CSS from `index.html`

## License

© 2026 Siddhant Kasture
