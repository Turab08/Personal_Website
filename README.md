# Personal Jekyll Site

This minimal Jekyll scaffold is compatible with GitHub Pages. It includes layouts, includes, a sample post, and modern CSS.

To preview locally:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Files to edit after generation:

- `_config.yml` — site title, description, navigation, and global settings.
- `_layouts/default.html` — overall HTML structure and includes.
- `_layouts/home.html` — homepage hero and recent posts.
- `_layouts/page.html` — generic page layout used by About/Projects/Resume.
- `_includes/header.html`, `_includes/nav.html`, `_includes/footer.html` — header, navigation, footer.
- `assets/css/style.css` — styles and visual tweaks.
- `index.md`, `about.md`, `projects.md`, `resume.md` — page content.
- `_posts/*.md` — blog posts.
