---
layout: default
title: Joseph Dalton - Portfolio
permalink: /projects/
---

<style>
.project-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
  padding-bottom: 2rem;
}

@media (max-width: 900px) {
  .project-gallery {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .project-gallery {
    grid-template-columns: 1fr;
  }
}

.gallery-item {
  display: flex;
  align-items: stretch;
}

.gallery-item a {
  display: flex;
  flex-direction: column;
  width: 100%;
  text-decoration: none;
  height: 100%;
}

.gallery-item img {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
  border-radius: 6px;
}

.gallery-item p {
  margin-top: 0.75rem;
  line-height: 1.4;
  text-align: center;
  white-space: normal;
  overflow-wrap: break-word;
}
</style>

<div class="gallery-container">
  <div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>