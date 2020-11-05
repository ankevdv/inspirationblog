---
title: BLOG
ondertitel: 'Documenting graphic design inspiration since 2020'
layout: 'layouts/blog.html'
---

<div class="blog">
{%- for post in collections.post | reverse -%}
  <div class="bloglink">
    <img class="fotopost" src='{{ post.data.afbeelding }}'>
    <div class="infopost">
      <a class="blogtitel" href="{{ post.url | url }}">{{ post.data.overviewtitel }}</a>
      <a class="blogdate" href="{{ post.url | url }}">{{ post.data.datum }}</a>
      <a href="{{ post.url | url }}">{{ post.data.description }}</a>
      <a class="blogbutton" href="{{ post.url | url }}">{{ post.data.button }}</a>
    </div>
 </div>
{%- endfor -%}
</div>
