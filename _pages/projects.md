---
layout: default
title: Bilal Mahmood - Portfolio
permalink: /projects/
---

<div class="gallery-container">
  <div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ site.baseurl }}{{ project.url }}">
          <img src="{{ site.baseurl }}{{ project.image }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>

