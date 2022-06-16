---
layout: page
title: Research, Pedagogy, and Discovery Seminar
nav_order: 2
description: >-
    8-week RPD Seminar
currWeekNumber: 1
---

# Research, Pedagogy, and Discovery Seminar

[About the Seminar]({{site.baseurl}}/rpd_project){: .btn .btn-blue}
[Project Specs]({{site.baseurl}}/rpd_project){: .btn .bg-yellow-200 .text-grey-dk-250 }

### Weekly Schedule
Subject to change. Jump to current week [here](#week-{{page.currWeekNumber}}) for the latest updates.

{% for schedule in site.schedules %}
    {% if schedule.name == "RPD" %}
        {{ schedule }}
    {% endif %}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
