# gomi0.net

Barebones personal blog powered by GitHub Pages and Jekyll.

## Adding a New Blog Post

Create a new `.md` file inside the `_posts/` folder named with the date and slug:

`_posts/YYYY-MM-DD-post-title.md`

At the very top of the file, include the front matter with `title`, `date`, and `tags`:

```markdown
---
title: "My New Post"
date: 2026-10-19
tags: [thoughts, misc]
---

Write your blog entry here using standard Markdown.
```

Commit and push the file to GitHub. GitHub Pages will automatically rebuild the site, add the post to the homepage, and add any new tags to the top navigation bar.
