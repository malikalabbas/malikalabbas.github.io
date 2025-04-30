---
layout: page  
title: "Projects"  
permalink: /projects/  
---

<div class="projects-grid">
  {% for p in site.projects %}
    <a class="project-card" href="{{ p.url }}">
      <h3>{{ p.title }}</h3>
    </a>
  {% endfor %}
</div>

