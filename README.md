# lujoril.github.io

Source for my portfolio site, built with Jekyll and served by GitHub Pages at https://lujoril.github.io.

## Editing

| What | Where |
| --- | --- |
| Home page, interests, contact | `index.html` |
| Experience | `work.md` |
| Projects | `_data/projects.yml` (title, images, optional summary, tags, links) |
| Articles | Markdown files in `_posts/` named `YYYY-MM-DD-title.md`. See `_drafts/example-article.md` |
| Skills | `skills.html` |
| Menu, footer links | `_config.yml` |
| Colors and styling | `assets/css/site.scss` (color variables at the top) |

## Preview locally (optional)

Requires Ruby: `bundle install` then `bundle exec jekyll serve --drafts`, then open http://localhost:4000.

Originally based on the [Contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme (public domain).
