# My Blog

A minimal blog powered by GitHub Pages and Jekyll.

## Local Development

To run locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Adding Posts

Create new posts in the `_posts` directory with the format:
`YYYY-MM-DD-title.md`

Each post should start with front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0500
categories: [category1, category2]
---
```
