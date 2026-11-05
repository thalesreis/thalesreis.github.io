---
title: How this site is published
description: A Markdown file in this repository becomes a page on GitHub Pages.
date: 2026-11-06
---

This site is the [`thalesreis.github.io`](https://github.com/thalesreis/thalesreis.github.io) repository. GitHub hosts the built files at this address. There is no server and no database behind a post.

A post is a Markdown file in `src/posts`. The file name starts with the date:

```text
src/posts/2026-11-06-how-this-site-is-published.md
```

[Eleventy](https://www.11ty.dev/) turns that file into `/how-this-site-is-published/`. The block at the top of the file is the title, the date, and the one-line summary that shows up on the home page.

Pushing `main` runs a GitHub Actions workflow. The workflow installs dependencies, builds the HTML, and deploys it to GitHub Pages. A new post is usually live within a couple of minutes.

To preview locally:

```bash
npm install
npm run dev
```

That serves the site at `http://localhost:8080`. Add `draft: true` under the title if the post should appear in that preview and stay out of the published build.
