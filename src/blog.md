---
title: BLOG
ondertitel: 'Documenting graphic design inspiration since 2020'
layout: 'layouts/blog.html'

pagination:
  data: collections.blog
  size: 2
permalink: 'blog{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: '< See newer posts'
paginationNextText: 'See older posts >'
paginationAnchor: '#post-list'
---
