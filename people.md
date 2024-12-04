---
layout: default
title: People
---

# Meet Our Team

<div class="team">
  {% for person in site.data.people %}
  <div class="member">
    <img src="{{ site.baseurl }}/assets/images/{{ person.image }}" alt="{{ person.name }}" width="150">
    <h3>{{ person.name }}</h3>
    <p><strong>{{ person.role }}</strong></p>
    <p>{{ person.bio }}</p>
  </div>
  {% endfor %}
</div>
