---
layout: default
title: Publications
---

# Publications

<ul>
  {% for publication in site.data.publications %}
  <li>
    <strong>{{ publication.title }}</strong><br>
    {{ publication.authors }}<br>
    <em>{{ publication.journal }}</em>, {{ publication.year }}.<br>
    <a href="{{ publication.link }}">[Read more]</a>
  </li>
  {% endfor %}
</ul>

