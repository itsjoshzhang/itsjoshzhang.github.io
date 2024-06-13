---
layout: page
title: Repos
permalink: /repos/ 
nav: true
nav_order: 2
---

Most of my project repositories are private. Please contact [joshzhang@berkeley.edu](mailto:joshzhang@berkeley.edu) for more info. While you're here, go check out [my Github](https://github.com/itsjoshzhang) and [my Linkedin](https://www.linkedin.com/in/itsjoshzhang/) for quick links to my work.

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}