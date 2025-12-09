layout: default
title: <"Sean McCarey"> - Portfolio
permalink: "/projects/2025-LinearActuator.md"
<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ [project.url](https://github.com/Cornell-MAE-UG/fa25-portfolio-stm223-tech/blob/main/_projects/2025-LinearActuator.md) | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
