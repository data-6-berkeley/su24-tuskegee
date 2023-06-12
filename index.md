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

{: .mb-2}
<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
</div>

[Coding Bootcamp]({{site.baseurl}}/bootcamp){: .btn .btn-purple .mr-2}
[RPD Seminar]({{site.baseurl}}/rpd){: .btn .btn-green}
<br/>
[Data 8](http://data8.org/su22/){: .btn .btn-outline}
[Data 6](http://data6.org/su22/){: .btn .btn-outline}

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

The below schedule is also available as a [Google Sheet](https://docs.google.com/spreadsheets/d/1Vlw94iLol_GNUcunarYZ5W1MvH89-TukYpUaNiqU7tI/edit?usp=sharing){:target="_blank"}.

Click on the tabs below to switch between weeks.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQsJ3hH0mhN6M6hdG7g6n76WPiIyB7gK0bfgr7QbmAdE7Oz72v3wPOGg4Ep39GEyVX0eDmY7wyhsO8j/pubhtml?widget=true&amp;headers=false" width=1100 height=600></iframe>
