---
layout: default
title: Insights and Updates
---

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    <p>{{ post.excerpt }}</p>
  </li>
{% endfor %}
</ul>
