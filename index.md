---
layout: default
title: 'Visual Oddity and Perceived Comfort in Everyday Scenes'
style: >-
  .doc_refs ul {
    list-style: none;
    padding-left: 0;
  }
  .doc_refs ul li {
    padding-left: 2em;
    text-indent: -1.333em;
  }
---

# Visual Oddity and Perceived Comfort in Everyday Scenes

{%- comment -%}
Section paths are relative to this page's own folder, so this file works
whether the repo is checked out as `thesis/thesis1` or as the submodule
`thesis/visual-oddity-perceived-comfort`.
{%- endcomment -%}
{% assign here = page.path | remove: page.name %}

{% assign path = here | append: "abstract.html" %}
{% assign abstract = site.pages | where: "path", path | first %}
{{ abstract.content }}

{% assign path = here | append: "introduction.md" %}
{% assign introduction = site.pages | where: "path", path | first %}
{{ introduction.content | markdownify }}

{% assign path = here | append: "method.md" %}
{% assign method = site.pages | where: "path", path | first %}
{{ method.content | markdownify }}

{% assign path = here | append: "results.md" %}
{% assign results = site.pages | where: "path", path | first %}
{{ results.content | markdownify }}

{% assign path = here | append: "discussion.md" %}
{% assign discussion = site.pages | where: "path", path | first %}
{{ discussion.content | markdownify }}

<div class="doc_refs">
{% assign path = here | append: "references.md" %}
{% assign references = site.pages | where: "path", path | first %}
{{ references.content | markdownify }}
</div>

<hr/>
