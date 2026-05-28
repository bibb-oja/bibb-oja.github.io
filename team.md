---
layout: page
title: Team
permalink: /team/
---

# Our Team

The OJA research initiative brings together researchers from various disciplines to analyze job advertisement data.

## Team Members

{% assign members = site.data.team.members %}

{% for member in members %}
### {{ member.name }}

**{{ member.role }}** 
{% if member.affiliation %}*{{ member.affiliation }}*{% endif %}

{{ member.bio }}

{% endfor %}

## Institutional Context

We are supported by [BIBB](https://www.bibb.de/) (Bundesinstitut für Berufsbildung) but maintain an independent research focus on occupational data analysis.

## Contact

For inquiries about our research or collaboration opportunities, please reach out through the contacts listed above.
