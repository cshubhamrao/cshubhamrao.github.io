# How to work with this repository

## Core Commands
- **Run Dev Server**: `hugo server -D` (drafts enabled)
- **Build Production**: `hugo --minify` (output to `/public`)
- **Resize OG Image**: `sips -Z 1200 static/og-image.png && sips -c 630 1200 static/og-image.png` (macOS)

## Architecture
- **Framework**: Hugo (Static Site Generator)
- **Theme**: PaperMod (submodule at `themes/PaperMod`)
- **Config**: `config.yml` (YAML format, profile mode enabled)
- **Deployment**: GitHub Actions -> GitHub Pages (source: `dot-dev` branch)

## Content Management
- **Posts**: Create in `content/posts/` (use `hugo new posts/my-post.md`)
- **Images**: Place in `static/` (referenced as `/image.png` in markdown)
- **Resume**: Update content in `content/about.md` directly.

## AI & SEO
- **llms.txt**: Maintain at `static/llms.txt` for AI crawlers.
- **OG Image**: `static/og-image.png` (Generated, 1200x630).
- **JSON-LD**: Built-in via PaperMod (`env: production` in config).
