---
chapter: Isolating work
layout: slide
title: ''
tags:
- isolating-work
---

{% capture notes %}
* Version patches of large change sets
* Stage interactively on command line
* Revise to-be-committed patch
{% endcapture %}
{% include hydeslides/core/notes %}

```bash
# Unstage by patch
$ git reset -p [file]
```
