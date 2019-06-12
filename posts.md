---
layout: page
title:  "Crazed ramblings"
---
<ul>
  {% for post in site.posts %}
    <li>
      <h1><a href="{{ post.url }}">{{ post.title }} -- ({{ post.date | date: '%B %d, %Y' }})</a></h1>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


