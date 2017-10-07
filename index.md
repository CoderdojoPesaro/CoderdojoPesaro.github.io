---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: index
title: Home
---


<h1>Blog Posts</h1>
<ul class="posts">
  {% for post in site.posts %}
    <li>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </li>
  {% endfor %}
</ul>
