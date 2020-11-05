---
title: BLOG
ondertitel: 'Documenting graphic design inspiration since 2020'
layout: 'layouts/blog.html'
---

<div class="blog">
{%- for post in collections.post | reverse -%}
  <div class="bloglink">
    <img src='{{ post.data.afbeelding }}'>
    <a class="blogtitel" href="{{ post.url | url }}">{{ post.data.title }}</a>
    <a class="blogdate" href="{{ post.url | url }}">{{ post.data.datum }}</a>
    <a href="{{ post.url | url }}">{{ post.data.description }}</a>
    <a class="blogbutton" href="{{ post.url | url }}">{{ post.data.button }}</a>
 </div>
{%- endfor -%}
</div>
