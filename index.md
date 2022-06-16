---
layout: home
title: Home
nav_order: 1
nav_exclude: false
permalink: index.html
seo:
  type: Course
  name: Just the Class
---

# Tuskegee Scholars: Research, Pedagogy, and Discovery

{: .mb-2 }
UC Berkeley, Summer 2022
{: .mb-2 .fs-6 .text-grey-dk-000 }

{: .mb-2 }
<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

**Room:** SOCS 174 (through July 1); Evans 6 (July 5th onwards)

{: .mb-0 .fs-5 .text-grey-dk-000 }
<!--{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>-->

## Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
