---
layout: page
title: Staff
description: Data 6 Summer 2022 Course Staff.
---

# Staff

Read more about our amazing Data 6 course staff below! We're all current or recent Berkeley undergraduates, so feel free to reach out with any questions about life at UC Berkeley, the data science major, or anything else Cal related!

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}


## Undergraduate Student Instructors (uGSIs)

{% assign teaching_assistants = site.staffers | where: 'role', 'uGSI' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}

## Tutors

{% assign tutors = site.staffers | where: 'role', 'Tutor' %}
{% for staffer in tutors %}
{{ staffer }}
{% endfor %}
