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

## Adding images to a post

1. Upload the image to the `assets/blog/` folder (**Add file → Upload files**), e.g. `assets/blog/query-plan.png`.
2. In the post, use either of these:

```
![Query plan before the index](/assets/blog/query-plan.png)
```

or, with a caption under the image:

```
<figure>
  <img src="/assets/blog/query-plan.png" alt="Query plan before the index">
  <figcaption>The query plan before adding the composite index.</figcaption>
</figure>
```

## Look

The blog is a simple white page with original pixel-art decorations: clouds and a bird drift across the sky, and a small pixel world (trees, rocks, bushes, flowers, a bunny and a slime) sits at the bottom of every page. The sprites are SVG files in `assets/blog/sprites/`, styled in `assets/blog.css`.
