---
layout: default
title: Bilal Mahmood - Portfolio
permalink: /projects/
---

<div class="gallery-container">
  <div class="project-gallery">
    {% for project in site.projects %}
      {% assign project_url = project.url | relative_url %}
      {% assign project_image = project.image | relative_url %}
      <div class="gallery-item">
        <a href="{{ project_url }}">
          <img src="{{ project_image }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>



