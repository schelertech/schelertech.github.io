# Schelertech Blog

Personal IT support blog for [blog.schelertech.com](https://blog.schelertech.com), built with [Jekyll](https://jekyllrb.com/) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://127.0.0.1:4000](http://127.0.0.1:4000).

## Writing a post

Create a new Markdown file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
title: "Your title"
date: 2026-04-07 09:00:00 -0400
categories:
  - Blog
  - IT Support
tags:
  - helpdesk
---

Your content here.
```

Optional local helper:

```bash
bundle exec jekyll post "Your title"
```

## Site structure

| Path | Purpose |
| --- | --- |
| `_posts/` | Blog posts |
| `_pages/` | About, archives, 404 |
| `_data/navigation.yml` | Top navigation |
| `_config.yml` | Site settings and theme options |
| `assets/images/` | Images and author avatar |

## Deploy

Pushes to `master` publish through GitHub Pages to `blog.schelertech.com`.
