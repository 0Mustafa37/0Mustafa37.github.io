# 0mustafa37.github.io

Personal website and blog of Mustafa Mohammed Ali, served by GitHub Pages.

- `index.html` is the home page (plain HTML and CSS).
- `blog/` is the blog index, built by Jekyll.
- `_posts/` holds the blog posts, one Markdown file each.

## Writing a new post

1. In GitHub, open the `_posts` folder and click **Add file → Create new file**.
2. Name it `YYYY-MM-DD-short-title.md`, for example `2026-11-15-postgres-indexes.md`.
3. Start the file with this header, then write the post in Markdown below it:

```
---
layout: post
title: "Your post title"
description: One line shown under the title on the blog page.
tags: [django, postgresql]
---

Your post starts here.
```

4. Click **Commit changes**. The post appears at `/blog/` within a minute or two.

Images go in `assets/` and are used like `![caption](/assets/my-image.png)`.
