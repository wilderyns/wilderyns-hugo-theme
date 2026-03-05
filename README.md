# Wilderyns Hugo Theme

Wilderyns is a custom Hugo theme for a personal site that combines:

- long-form blog posts
- project case studies
- career/skills profile content

## Features

- Purpose-built layouts for blog, projects, and career sections
- Optional Cloudflare Web Analytics and Google Ads integration points

## Requirements

- Hugo Extended `>= 0.120.0`

## Install 

From Hugo root:

```bash
git submodule add <YOUR_THEME_REPO_URL> themes/wilderyns
```

Then set the theme in `hugo.yaml`:

```yaml
theme: wilderyns
```

## Local Development

Run the site with drafts:

```bash
hugo server --buildDrafts --disableFastRender
```

## Theme Structure

- `layouts/_default/`: base, list, single, taxonomy templates
- `layouts/blog/`: blog-specific list/single templates
- `layouts/projects/`: project-specific list/single templates
- `layouts/career/`: career landing template
- `layouts/partials/`: reusable head/header/footer and helper partials
- `layouts/shortcodes/`: custom shortcodes (for example `postfigure`)
- `assets/css/`: theme stylesheet sources
- `theme.toml`: Hugo theme metadata

## License

MIT (see `theme.toml` metadata)
