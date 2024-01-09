---
layout: home
title: Home
nav_order: 1
seo:
  type: Course
  name: Filmmaking Basics DeCal
---

# Filmmaking Basics DeCal
{: .mb-2}
{{ site.description }}
{: .fs-6 .fw-300}

<!-- {% if site.announcements %}
{{ site.announcements.last }}
{% endif %} -->

## Weekly Schedule
{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

<!-- ## Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %} -->
