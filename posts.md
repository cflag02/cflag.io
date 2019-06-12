---
layout: page
title:  "Crazed ramblings"
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }} -- ({{ post.date | date: '%B %d, %Y' }})</a></h2>
      <h3>{{ post.excerpt }}</h3>
    </li>
  {% endfor %}
</ul>


