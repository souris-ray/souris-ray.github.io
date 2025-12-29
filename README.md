# Souris Ray - ASMR Scriptwriting Portfolio

A dark academia themed portfolio website for showcasing ASMR scripts, built with Jekyll and GitHub Pages.

## 🌙 Features

- **Dark Academia Aesthetic**: Rich browns, antique golds, and elegant typography
- **Responsive Design**: Beautiful on desktop, tablet, and mobile
- **Script Filtering**: Sort and filter scripts by date, type, and tags
- **Sample Scripts**: Three example scripts included to demonstrate the system
- **Easy Customization**: All colors and fonts defined in CSS variables

## 📝 Quick Start

### 1. Update Site Information

Edit [_config.yml](_config.yml) to customize your site:

```yaml
title: Souris Ray
tagline: "[Your tagline here]"
description: Your description
discord_url: "https://discord.gg/your-server"
```

### 2. Add Your Own Scripts

Create new script files in the `_scripts/` folder. Use this template:

```yaml
---
title: "Your Script Title"
description: "Brief description for the card view"
word_count: 1250
date: 2025-12-15
tags: [comfort, sleep, roleplay]
type: ambience  # or: roleplay, companion, study, etc.
pdf: /assets/pdfs/your-script.pdf
---

Your script content here in Markdown format...
```

### 3. Customize Content

- **About Page**: Edit [about.md](about.md)
- **Guidelines**: Edit [guidelines.md](guidelines.md)
- **Landing Page**: Modify [index.md](index.md)

### 4. Upload PDFs

Place your script PDFs in `assets/pdfs/` and reference them in the script front matter.

## 🎨 Customization

### Colors

All colors are defined in [assets/css/main.css](assets/css/main.css):

```css
:root {
  --color-bg-primary: #1a1410;
  --color-gold-antique: #d4a574;
  /* etc... */
}
```

### Typography

Five Google Fonts are used:
- **Cormorant Garamond**: Site title
- **Playfair Display**: Headings
- **Libre Baskerville**: Script titles
- **Crimson Text**: Body text
- **Source Sans 3**: Labels and metadata

## 📁 File Structure

```
sourisray.github.io/
├── _config.yml           # Site configuration
├── _layouts/            # Page templates
├── _includes/           # Reusable components
├── _scripts/            # Your script collection
├── assets/
│   ├── css/main.css    # Stylesheet
│   ├── js/filter.js    # Filtering functionality
│   └── pdfs/           # Script PDFs
├── index.md            # Landing page
├── scripts.html        # Scripts list page
├── about.md            # About page
└── guidelines.md       # Guidelines page
```

## 🚀 Deployment

This site is designed for GitHub Pages. Just push your changes and GitHub will automatically build and deploy.

## ✨ Sample Scripts

Three sample scripts are included - replace these with your own content.

---

© 2025 Souris Ray. Built with care for the ASMR community.