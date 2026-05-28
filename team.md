---
layout: page
title: Team
permalink: /team/
description: Meet the research team driving OJA job advertisement analysis.
---

<p class="section-intro">The OJA team combines computational, social science, and labor market expertise to analyze occupational data from job postings.</p>

<div class="member-grid">
  {% assign members = site.data.team.members %}
  {% for member in members %}
    <article class="card member-card">
      <h3>{{ member.name }}</h3>
      <p class="meta">{{ member.role }}{% if member.affiliation %}, {{ member.affiliation }}{% endif %}</p>
      <p>{{ member.bio }}</p>
    </article>
  {% endfor %}
</div>

<section class="content-card">
  <h2>Institutional context</h2>
  <p>We are supported by <a href="https://www.bibb.de/">BIBB</a>, while keeping a focused research agenda on occupation-related data and student collaboration.</p>
</section>

<section class="content-card">
  <h2>Contact</h2>
  <p>For collaborations or student topic inquiries, please contact the team members listed above.</p>
</section>
