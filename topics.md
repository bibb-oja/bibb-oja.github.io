---
layout: page
title: Student Topics
permalink: /topics/
---

# Student Research Topics

We welcome students from diverse backgrounds. Below are potential research directions:

{% assign topics = site.data.topics.categories %}

{% for category in topics %}
## {{ category.name }}

{{ category.description }}

{% for topic in category.items %}
- **{{ topic.title }}**: {{ topic.description }}
{% endfor %}

---
{% endfor %}

## How to Get Started

Interested in one of these topics? Contact our team to discuss specific research questions and project scope.
