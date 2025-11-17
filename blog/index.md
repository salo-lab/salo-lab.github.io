---
title: Blog
nav:
  order: 4
  tooltip: Musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %} Blog

Updates, announcements, and occasional notes from the Salo Lab.

{% include section.html %}

{%
  include list.html
  data="posts"
  component="post-excerpt"
%}

{% comment %}
Enable these later when you have more posts:

{% include search-box.html %}
{% include tags.html tags=site.tags %}
{% include search-info.html %}
{% endcomment %}
