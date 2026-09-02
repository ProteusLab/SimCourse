---
layout: page
title: Объявления
nav_exclude: true
description: Лента объявлений курса.
---

# Объявления

Объявления хранятся в каталоге `_announcements` и отображаются с помощью шаблона `_layouts/announcement.html`.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
