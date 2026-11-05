# thalesreis.github.io

Personal site for Thales Reis, published at <https://thalesreis.github.io>.

Posts are Markdown files. [Eleventy](https://www.11ty.dev/) builds them into a static site, and GitHub Actions deploys that site to GitHub Pages on every push to `main`.

## Add a post

Create a file in `src/posts` whose name starts with the date:

```text
src/posts/2026-11-06-my-new-post.md
```

```markdown
---
title: My new post
description: One sentence for the home page.
date: 2026-11-06
---

The post goes here.
```

Commit the file and push `main`. The site updates after the Actions workflow finishes.

`draft: true` in that header shows the post in the local preview and leaves it out of the published build.

## Preview locally

```bash
npm install
npm run dev
```

The preview runs at <http://localhost:8080>.
