---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order. Powered by jekyll-scholar.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography %}

</div>
<br/>
## repositories

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

## public reports

- Dissemination, Exploitation, and Communication Plan (v1.0) - <a href="../assets/pdf/DEC.pdf">download</a>
- Data Management Plan (v1.0) - <a href="../assets/pdf/DMP.pdf">download</a>