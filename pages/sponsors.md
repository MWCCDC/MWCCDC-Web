---
layout: page
title: Our Sponsors
permalink: /sponsors/
---
## Our Sponsors

The MWCCDC is made possible by the generous support of our sponsors.

{% for s in site.data.sponsors %}
- **{{ s.name }}** ({{ s.tier }} sponsor) — [website]({{ s.url }})
{% endfor %}