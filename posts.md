---
layout: page
title:  "Rantings"
---
When I write words they will appear here:
{% for post in site.posts %}
  <li>
    <b><a href="{{ post.url }}">{{ post.title }} - ({{ post.date | date: '%B %d, %Y' }})</a></b>
  </li>
{% endfor %}


