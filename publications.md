---
layout: page
title: Publications
permalink: /publications/
---

# Publications

{% assign publications = site.data.publications.items %}

{% if publications.size > 0 %}
{% for pub in publications %}
### {{ pub.title }}
**{{ pub.authors }}** ({{ pub.year }})

{% if pub.journal %}*{{ pub.journal }}*{% endif %}
{% if pub.doi %}<a href="https://doi.org/{{ pub.doi }}" target="_blank">DOI: {{ pub.doi }}</a>{% endif %}

{{ pub.description }}

---
{% endfor %}
{% else %}
*Publications coming soon...*
{% endif %}
