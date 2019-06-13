---
layout: page
title:  "Rantings"
---
  <ul style="list-style: none;">
    {% for post in site.posts %}
      <li>
        <h3><a href="{{ post.url }}">{{ post.title }} - ({{ post.date | date: '%B %d, %Y' }})</a></h3>
      </li>
    {% endfor %}
  </ul>


