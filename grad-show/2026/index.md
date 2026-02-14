---
layout: default
title: Grad Show 2026
---

<h1>Grad Show 2026</h1>

<ul>
{% assign students_2026 = site.students | where: "grad_year", 2026 %}
{% for student in students_2026 %}
  <li><a href="{{ student.url }}">{{ student.name }}</a></li>
{% endfor %}
</ul>
