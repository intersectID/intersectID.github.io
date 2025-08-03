# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the INTERSECT 2025 symposium website - a Jekyll-based static site for an academic conference focusing on sustainability, technology, and society. The event brings together Indonesian academics, practitioners, and policy-makers at Stanford University.

## Development Commands

```bash
# Install dependencies
bundle install

# Start development server (runs on http://localhost:4000)
bundle exec jekyll serve

# Build for production
bundle exec jekyll build

# Clean build artifacts
bundle exec jekyll clean
```

## Architecture & Key Components

### Jekyll Configuration
- **_config.yml**: Main site configuration including URL, title, theme settings, and plugin configurations
- **Theme**: Beautiful Jekyll v5.0.0 - provides base layouts, includes, and styling
- **Plugins**: jekyll-redirect-from, jekyll-sitemap, jekyll-feed, jekyll-seo-tag

### Content Structure
- **Main Pages**: Markdown files in root (index.md, programs.md, competition.md, etc.)
- **Layouts**: Templates in `_layouts/` - base, page, post, minimal, home
- **Includes**: Reusable components in `_includes/` for headers, footers, navigation
- **Data**: Navigation structure defined in `_data/navigation.yml`

### Styling System
- **CSS Variables**: Defined in `beautifuljekyll-variables.css` for theming
- **Main Stylesheet**: `beautifuljekyll.css` contains core styles
- **Custom Styles**: Additional styles in various CSS files under `assets/css/`
- **Color Scheme**: Primary green (#039311) with professional color palette

### Key Technical Details
- **Front Matter**: All content pages require YAML front matter with title, layout, and optional metadata
- **Asset Organization**: 
  - Images: `/assets/img/`
  - PDFs: `/assets/pdf/` (competition documents, templates)
  - CSS/JS: `/assets/css/` and `/assets/js/`
- **Build Output**: `_site/` directory (gitignored)
- **Deployment**: GitHub Pages via CNAME file pointing to intersect.id

### Important Considerations
- **External Dependencies**: Competition submissions handled via external platform (intersect.papertrack.app)
- **Responsive Design**: Site uses Bootstrap grid system via theme
- **SEO**: Open Graph tags and structured data configured in theme
- **Comments**: Staticman configured but implementation depends on external service