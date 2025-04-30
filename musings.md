---
layout: page  
title: "Musings"  
permalink: /musings/  
---

Stuff I've written about

<div class="projects-grid">
  {% for p in site.musings %}
    <a class="project-card" href="{{ p.url }}">
      <h3>{{ p.title }}</h3>
    </a>
  {% endfor %}
</div>
