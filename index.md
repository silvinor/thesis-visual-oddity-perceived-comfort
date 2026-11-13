---
layout: default
title: 'Visual Oddity and Perceived Comfort in Everyday Scenes'
style: >-
  img { max-width: 100%; }
---

# Visual Oddity and Perceived Comfort in Everyday Scenes

{% assign abstract = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/abstract.html" | first %}
{{ abstract.content }}

{% assign introduction = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/introduction.md" | first %}
{{ introduction.content | markdownify }}

{% assign method = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/method.md" | first %}
{{ method.content | markdownify }}

{% assign results = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/results.md" | first %}
{{ results.content | markdownify }}

{% assign discussion = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/discussion.md" | first %}
{{ discussion.content | markdownify }}

{% assign references = site.pages | where: "path", "thesis/visual-oddity-perceived-comfort/references.md" | first %}
{{ references.content | markdownify }}

<hr/>
