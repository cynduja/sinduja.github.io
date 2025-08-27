# Two column project theme for GitHub Pages

What you get
- Jekyll project with a 'projects' collection
- Each project uses a two column layout: write up on the left and an image on the right
- Responsive on mobile

How to use
1) Upload everything in this folder to your `YOUR-USERNAME.github.io` repository
2) Create a new project by copying one of the files in `projects/` and editing the front matter
3) Put your image file in `assets/img/` and set the `image:` path
4) Visit `https://YOUR-USERNAME.github.io/projects/`

Front matter example
```
---
layout: project
title: Your project title
date: 2025-08-01
summary: One or two sentences about the project
image: /assets/img/your-photo.jpg
alt: Accessible description of the image
caption: Optional caption
links:
  - text: Read the story
    url: https://example.com/story
  - text: Data repo
    url: https://github.com/you/repo
---
Your narrative in Markdown.
```
