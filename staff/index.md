---
layout: default
permalink: /staff/
title: Staff
desc: Information about the permanent staff for The Alchemist Encodes. These will be frequently returning names.
---
{% include construction.html %}
## Meet the staff ##

The people currently making most of The Alchemist Encodes a reality to work on
our projects are a small but diverse group. Some or all of these names can
generally be found on all of our releases.

{% for s in site.data.staff %}
- Name: {{ s.name }}<br />
Contributions: {{ s.roles }}
{% endfor %}
