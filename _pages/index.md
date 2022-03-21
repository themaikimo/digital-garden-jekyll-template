---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

<p style="padding: 3em 1em; background: #faf0d9; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>

This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

<style>
  .wrapper {
    max-width: 46em;
  }
</style>


<!-- MWJ 20220321: Moved here from _layouts/note.html -->
<hr />
<p>Here are all the notes in this garden, along with their links, visualized as a graph.</p>

{% include notes_graph.html %}
