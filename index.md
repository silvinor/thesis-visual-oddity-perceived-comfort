---
layout: default
title: 'Visual Oddity and Perceived Comfort in Everyday Scenes'
description: >-
  What looks out of place feels uncomfortable mostly because it is unexpected. In this study, adding a harmless out-of-place element to an everyday scene made it less comfortable to imagine entering, and that effect ran through how unexpected the scene looked.
author: Silvino Rodrigues
date: 2026-12-06
seo:
  type: ScholarlyArticle
image: ./assets/img/unexpected-pelican.min.jpg
js:
  - https://cdn.jsdelivr.net/npm/prismjs@1.30.0/prism.min.js
  - https://cdn.jsdelivr.net/npm/prismjs@1.30.0/components/prism-python.min.js
  - https://cdn.jsdelivr.net/npm/prismjs@1.30.0/plugins/line-numbers/prism-line-numbers.min.js
css:
  - prism-bs5.css
  - https://cdn.jsdelivr.net/npm/prismjs@1.30.0/plugins/line-numbers/prism-line-numbers.min.css
style: >-
  .doc_refs ul {
    list-style: none;
    padding-left: 0;
  }
  .doc_refs ul li {
    padding-left: 2em;
    text-indent: -1.333em;
  }
  code { font-size: .75em !important; }
  .table thead th small { font-weight: normal; }
  .table tbody th { font-weight: normal; }
  .table td, .table th { width: 20%; }
  .table tbody td small { font-size: 8px; line-height: 1.5; display: inline-block; }
  .table tbody td img { border-radius: 0.5em; min-width: 90px; }
  .table td.column-0 { background-color: rgba(127,127,127,0.25); }
  #appendix-c section, #appendix-d section { margin-top: 3rem; }
  .spss-title { font-weight: bold; margin: 1.75rem 0 0.5rem; }
  .spss { font-size: 0.85rem; width: auto; font-variant-numeric: tabular-nums; }
  .spss th, .spss td { padding: 0.25rem 0.6rem; vertical-align: bottom; }
  .spss thead th { font-weight: normal; }
  .spss tbody th { font-weight: normal; text-align: left; white-space: nowrap; }
  .spss tbody td { text-align: right; white-space: nowrap; }
  .spss-note { font-size: 0.8rem; margin: 0; }
  .spss-output { font-size: 0.8rem; line-height: 1.35; padding: 1rem; border: 1px solid rgba(127,127,127,0.35); border-radius: 0.5em; overflow-x: auto; }
  p[align="center"] { color: #678; text-align: center; }
  body { font-variant-ligatures: no-contextual; }  
script: >-
  document.addEventListener('DOMContentLoaded', () => {
    document.querySelectorAll('p > strong:first-child').forEach(label => {
      if (/^(Figure|Table)\s/.test(label.textContent)) {
        label.parentElement.classList.add('tsandfs');
      }
    });
  });
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

<p align="center" class="asterism">✦</p>

<hr/>
