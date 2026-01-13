---
layout: page
lang: en
title: Projects
permalink: /projects/
nav: true
nav_order: 4
display_categories: [work]
horizontal: false
---

<!-- pages/projects.md -->
{% comment %} 获取当前页面的语言，默认为 'en' {% endcomment %}
{% assign current_lang = page.lang | default: 'en' %}
{% comment %} 根据语言过滤项目 {% endcomment %}
{% if current_lang == 'zh' %}
  {% assign filtered_projects = site.projects | where: "lang", "zh" %}
{% else %}
  {% assign filtered_projects = site.projects | where_exp: "item", "item.lang != 'zh' or item.lang == nil" %}
{% endif %}

<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = filtered_projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = filtered_projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
