# Yaga Personal Portfolio Site

A clean, minimal Jekyll site to showcase your projects. Just write markdown files and they automatically appear as beautiful cards on your site!

## 🚀 Getting Started

### Prerequisites
- Ruby (2.7 or higher)
- Bundler

### Installation

1. Install dependencies:
```bash
bundle install
```

2. Run the site locally:
```bash
bundle exec jekyll serve
```

3. Open your browser to `http://localhost:4000`

## ✍️ Adding a New Project (Super Easy!)

Just create a new markdown file in the `_projects` folder. That's it!

### Example: `_projects/my-awesome-project.md`

```markdown
---
title: My Awesome Project
tagline: This catchy line appears on the card to make visitors click!
technologies:
  - Python
  - React
  - Docker
github: https://github.com/yourusername/my-project
demo: https://demo.example.com
---

## Description

Write your project details here in markdown!

## Features

- Feature 1
- Feature 2

## What I Learned

Share your experience...
```

### Project Front Matter Fields

- **title** (required): Project name
- **tagline** (required): Catchy one-liner that appears on the card
- **technologies**: List of technologies used (shows on card)
- **github**: Link to GitHub repository (optional)
- **demo**: Link to live demo (optional)

## 📝 Editing Content

- **Home page**: Edit `index.html`
- **About page**: Edit `about.md`
- **Site settings**: Edit `_config.yml` (change site title, description, etc.)
- **Styles**: Edit `assets/css/style.css`

## 🎨 Customization

1. Update your name and site info in `_config.yml`
2. Edit `about.md` to tell your story
3. Replace the example projects in `_projects/` with your own
4. Customize colors in `assets/css/style.css`

## 📁 Project Structure

```
.
├── _config.yml          # Site configuration
├── _layouts/            # Page templates
├── _projects/           # Your project markdown files (add new ones here!)
├── assets/css/          # Stylesheets
├── index.html           # Home page
├── about.md             # About page
└── Gemfile              # Ruby dependencies
```

## 🚢 Deployment

This site works great with GitHub Pages, Netlify, or any static hosting service.

### GitHub Pages
1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Select the branch to deploy

## 💡 Tips

- Keep taglines short and catchy (under 60 characters works best)
- Add 2-3 key technologies to each project card
- Use markdown formatting in your project descriptions
- Images work great in project descriptions

---

That's it! No complex code needed - just write markdown and publish!
