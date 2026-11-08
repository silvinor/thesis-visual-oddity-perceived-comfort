---
layout: default
title: 'Visual Oddity and Perceived Comfort in Everyday Scenes'
style: >-
  img { max-width: 100%; }
---

# Visual Oddity and Perceived Comfort in Everyday Scenes

{% assign abstract = site.pages | where: "path", "thesis/thesis1/abstract.html" | first %}
{{ abstract.content }}

{% assign introduction = site.pages | where: "path", "thesis/thesis1/introduction.md" | first %}
{{ introduction.content | markdownify }}

{% assign method = site.pages | where: "path", "thesis/thesis1/method.md" | first %}
{{ method.content | markdownify }}

{% assign results = site.pages | where: "path", "thesis/thesis1/results.md" | first %}
{{ results.content | markdownify }}

{% assign discussion = site.pages | where: "path", "thesis/thesis1/discussion.md" | first %}
{{ discussion.content | markdownify }}

{% assign references = site.pages | where: "path", "thesis/thesis1/references.md" | first %}
{{ references.content | markdownify }}

<hr/>
