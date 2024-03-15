---
layout: page
title: Students
permalink: /students/
description: members of the lab or group
nav: true
nav_order: 4
display_categories: [PhD student, Master student]
horizontal: false
---

<!-- pages/students.md -->
<div class="projects">
{% if site.enable_student_categories and page.display_categories %}
  <!-- Display categorized students -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_students = site.students | where: "category", category %}
  {% assign sorted_students = categorized_students | sort: "importance" %}
  <!-- Generate cards for each student -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for student in sorted_students %}
      {% include students_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for student in sorted_students %}
      {% include students.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display students without categories -->

{% assign sorted_students = site.students | sort: "importance" %}

  <!-- Generate cards for each student -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for student in sorted_students %}
      {% include students_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for student in sorted_students %}
      {% include students.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
