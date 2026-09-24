---
layout: page
title: Расписание
nav_order: 5
description: Недельное расписание занятий.
---

# Расписание

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
