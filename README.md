# Diea Calin - Personal Blog

A personal blog built with Jekyll.

## Local Development

### Prerequisites

- Ruby (version 3.0 or higher)
- Bundler

### Setup

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   bundle exec jekyll build
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

### Adding New Posts

Create a new file in the `_posts` directory with the format:
```
YYYY-MM-DD-title-of-post.md
```

Example:
```markdown
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: blog
---

Your post content here...
```

## Deployment

This site can be easily deployed to GitHub Pages or any static site hosting service.

### GitHub Pages

1. Push your changes to the repository
2. Enable GitHub Pages in repository settings
3. Select the branch to deploy from (usually `main`)

## Site Structure

- `_config.yml` - Site configuration
- `_layouts/` - Page templates
- `_posts/` - Blog posts
- `_includes/` - Reusable components
- `assets/` - CSS, images, and other static files
- `index.html` - Homepage
