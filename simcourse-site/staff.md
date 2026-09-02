---
layout: page
title: Преподаватели
nav_order: 5
description: Список преподавателей и ассистентов курса.
---

# Преподаватели

## Преподаватели

{% assign instructors = site.staffers | where: 'role', 'Lecturer' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Ассистенты

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
