---
layout: page
title: Publications
permalink: /publications/
description: A curated list of publications from the OJA research team.
---

<p class="section-intro">These publications present our methods and findings in job advertisement analysis, occupational trend detection, and labor-market research.</p>

<div class="publications-list">
  {% assign publications = site.data.publications.items %}
  {% if publications.size > 0 %}
    {% for pub in publications %}
      <article class="card publication-card">
        <h2>{{ pub.title }}</h2>
        <p class="meta">{{ pub.authors }} · {{ pub.year }}{% if pub.journal %} · {{ pub.journal }}{% endif %}</p>
        <p>{{ pub.description }}</p>
        {% if pub.doi and pub.doi != "" %}
          <p><a class="text-link" href="https://doi.org/{{ pub.doi }}" target="_blank">Read the publication</a></p>
        {% endif %}
      </article>
    {% endfor %}
  {% else %}
    <p>Publications coming soon...</p>
  {% endif %}
</div>
