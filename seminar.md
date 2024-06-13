---
layout: page
title: Research and Discovery Seminar
nav_order: 2
description: >-
  8-week RPD Seminar
currWeekNumber: 1
---

# Research and Discovery Seminar

[Project Specifications]({{site.baseurl}}/rpd_project){: .btn .bg-yellow-200 .text-grey-dk-250 }

**Room:** Dwinelle 247 ([map](https://maps.app.goo.gl/NtTEMabyopGyQU1u6))

### Weekly Schedule

Subject to change. Jump to current week [here](#week-{{page.currWeekNumber}}) for the latest updates.

<!--[Contact List of Guest Speakers](https://docs.google.com/spreadsheets/d/16DzemR4GISIfOX9patkE3V4eLKeeWA2IQ92QCk6a2oI/edit?usp=sharing){:target="_blank"}-->

{% for schedule in site.schedules %}
{% if schedule.name == "RPD" %}
{{ schedule }}
{% endif %}
{% endfor %}

{% for module in site.modules_rpd %}
<a name="week-{{module.weekNumber}}"></a>
{{ module }}
{% endfor %}
