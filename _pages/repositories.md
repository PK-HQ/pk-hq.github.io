---
layout: page
permalink: /Github/
title: repositories
description:
nav: true
nav_order: 4
---

{% comment %} Section 1: GitHub Users {% endcomment %}
{% if site.data.repositories.github_users %}
## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>
{% endif %}


{% comment %} Section 2: GitHub Repositories {% endcomment %}
{% if site.data.repositories.github_repos %}
## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}


{% comment %} Section 3: GitHub Trophies {% endcomment %}
{% if site.repo_trophies.enabled %}
  {% if site.data.repositories.github_users %} {# Check if users exist before looping for trophies #}

    ## GitHub Trophies {# Added heading for clarity #}

    {% for user in site.data.repositories.github_users %}
      {% if site.data.repositories.github_users.size > 1 %} {# Display user name only if multiple users #}
        <h4>{{ user }}'s Trophies</h4> {# Clarified heading #}
      {% endif %}
      <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
        {% include repository/repo_trophies.liquid username=user %}
      </div>
      {% unless forloop.last %} {# Add HR between users' trophies, but not after the last one #}
      ---
      {% endunless %}
    {% endfor %}
  {% endif %}
{% endif %}
