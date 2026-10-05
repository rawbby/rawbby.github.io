---
layout: page
title: Posts
permalink: /posts/
---

<ul class="post-list">
{%- for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: site.minima.date_format }}</span>
    <h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></h3>
    {%- if post.summary %}<p>{{ post.summary | escape }}</p>{% endif %}
  </li>
{%- endfor %}
</ul>
{%- if site.posts.size == 0 %}
<p>No posts yet.</p>
{%- endif %}
