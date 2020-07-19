---
title: "Hugo blog post workflow"
date: 2020-07-19T11:02:40+02:00
draft: false
toc: false
images:
tags:
  - hugo
  - blog post
  - workflow
---

[This is the project setup](https://gohugo.io/hosting-and-deployment/hosting-on-github/)

**Step 1**: `$ hugo posts/<post_name>.md`

**Step 2**: Edit post and preview with `$ hugo server -D`

**Step 3**: In blog post change `draft` to `false`

**Step 4**: Run `$ ./deploy.sh "Commit message"`
