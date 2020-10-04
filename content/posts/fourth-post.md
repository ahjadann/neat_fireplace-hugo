---
title: "Hugo blog post workflow"
date: 2020-07-19T11:02:40+02:00
lastmod: 2020-10-04T13:39:40+02:00
draft: false
toc: false
images:
tags:
  - hugo
  - blog post
  - workflow
---

[This is the project setup](https://gohugo.io/hosting-and-deployment/hosting-on-github/)

**Step 1**: `$ hugo new posts/<post_name>.md`

**Step 2**: Edit post and preview with `$ hugo server -D`

**Step 3**: In blog post change `draft` to `false`

**Step 4**: Run `$ ./deploy.sh "Commit message"`

**Step 5**: Commit changes to `public`.

---

In case of submodule errors check <https://gist.github.com/myusuf3/7f645819ded92bda6677>

