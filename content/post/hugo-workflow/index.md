---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hugo Workflow"
subtitle: ""
summary: ""
authors: [wilsonm]
tags: [hugo, working copy, textastic]
categories: [writing]
date: 2019-07-07T20:00:51-05:00
lastmod: 2019-07-07T21:14:51-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I have recently returned to keeping a blog. It has always been easy for me to start a blog but hard for me to keep it going. I have tried various CMS, including Wordpress, Drupal, Jekell, Octopress, and Hugo. My current favorite is [Hugo](https://gohugo.io/). I find it minimal, fast, and easy to use. My only real complaint is the fact that I needed to publish from my laptop. It turns out that is no longer the case.

By utilizing Hugo, Github, and Netlify, i can use a pipeline and publish automatically. Whenever I push an update to GitHub, Netlify will automatically rebuild the site. This has led me to create a new iOS workflow for myself. I can access the code for my site using Working Copy (WC) on my iOS devices. The content can be edited directly in WC but that can lead to issues. i have found it difficult to remember the needed frontmatter for new content. To solve this issue, I create several draft pieces of content. These serve as the basis for new posts. I still manage the code in WC but edit in Texttastic. The app Textastic allows me to duplicate a template and edit it. Once I am done in Textastic, I go back to WC and commit and push changes. The site will then rebuild. 
