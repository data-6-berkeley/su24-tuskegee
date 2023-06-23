---
layout: page
title: Coding Bootcamp
nav_order: 2
description: >-
    2-Week Pre-Data 6 Curriculum
---

# Pre-Data 6 Coding Bootcamp

Coding bootcamp for the first two weeks of the Tuskegee Scholars program.
All days start at 10am. Please check the [Home](../) page for precise times.

**Room:** Evans 45 ([map](https://goo.gl/maps/hNHgeyuVVt3Y5k6S6){: target="_blank"})

{% for schedule in site.schedules %}
    {% if schedule.name == "Bootcamp" %}
        {{ schedule }}
    {% endif %}
{% endfor %}

{% for module in site.modules_bootcamp %}
{{ module }}
{% endfor %}
