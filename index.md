---
layout: home
title: "GISNerd - Portfolio"
---

# Welcome to GISNerd

**Disclaimer: These projects and the data used are strictly for demonstration and coding exercise purposes. They should not be used for any real analysis or decision-making.**

## Portfolio Projects

<div class="projects-list">
  {% raw %}{% for project in site.projects %}{% endraw %}
  <div class="project-card">
    <h3><a href="{% raw %}{{ project.url | relative_url }}{% endraw %}">{% raw %}{{ project.title }}{% endraw %}</a></h3>
    <p>{% raw %}{{ project.excerpt }}{% endraw %}</p>
    <a class="btn" href="{% raw %}{{ project.url | relative_url }}{% endraw %}">View Project →</a>
  </div>
  {% raw %}{% endfor %}{% endraw %}
</div>

## Explore More

Visit my main site for more insights and projects in GIS: [GISNerd.com](https://gisnerd.com)

---

© 2025 GISNerd. All rights reserved.