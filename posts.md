---
layout: page
title:  "Rantings"
---
  <ul>
    {% for post in site.posts %}
      <li>
        <b><a href="{{ post.url }}">{{ post.title }} - ({{ post.date | date: '%B %d, %Y' }})</a></b>
      </li>
    {% endfor %}
  </ul>


