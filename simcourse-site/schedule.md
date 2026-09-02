---
layout: page
title: Расписание
nav_order: 4
description: Недельное расписание занятий.
---

# Расписание

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
