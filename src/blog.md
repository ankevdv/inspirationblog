---
title: BLOG
layout: 'layouts/blog.html'
---

<ul class="blog">
{%- for post in collections.post | reverse -%}
  <li class="bloglink">
    <img src='{{ post.data.afbeelding }}'>
    <a class="blogtitel" href="{{ post.url | url }}">{{ post.data.title }}</a>
    <a href="{{ post.url | url }}">{{ post.data.description }}</a>
    <a href="{{ post.url | url }}">{{ post.data.button }}</a>
 </li>
{%- endfor -%}
</ul>

Loret ipsum dolor sit amet, consectetur adipiscing elit. Proin feugiat viverra feugiat. Nulla mattis urna ac laoreet convallis. Mauris tempor lacinia condimentum. Fusce volutpat sollicitudin nunc, eu porttitor nulla varius non. Nam in sagittis purus, id volutpat turpis. Fusce nibh nulla, finibus sed enim vel, ullamcorper consectetur lectus. Donec sit amet augue augue. Proin eros lectus, pulvinar sit amet ligula ut, malesuada mattis sem. Mauris egestas tellus vitae quam pretium dictum hendrerit nec neque. Nullam id metus ultrices, tincidunt nisi in, congue arcu. Aliquam eu commodo massa. Fusce placerat orci vitae sollicitudin aliquet.
