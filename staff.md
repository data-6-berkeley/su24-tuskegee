---
layout: page
title: Tuskegee Scholars Staff
nav_order: 4
---

{: .mb-2}
<div>
{% assign instructors = site.staffers | where: 'role', 'Faculty Director' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'RPD Facilitator' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

<div>
{% assign instructors = site.staffers | where: 'role', 'Bootcamp Facilitator' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>
