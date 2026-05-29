---
layout: page
title: Student Topics
permalink: /topics/

---

<p class="section-intro">Potential student projects for computer science, digital humanities, social science, and economics focusing on job advertisement analysis.</p>

{% assign topics = site.data.topics.categories %}

{% for category in topics %}
  <section class="topic-category">
    <h2>{{ category.name }}</h2>
    <p>{{ category.description }}</p>
    <div class="topic-grid">
      {% for topic in category.items %}
        <article class="card topic-card">
          <h3>{{ topic.title }}</h3>
          <p>{{ topic.description }}</p>
        </article>
      {% endfor %}
    </div>
  </section>
{% endfor %}

<section class="content-card">
  <h2>How to get started</h2>
  <p>Interested in one of these topics or have other ideas? Contact our team to define a clear project scope, research question, and timeline.</p>
</section>
