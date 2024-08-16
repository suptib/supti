---
layout: page
title: Experience 
permalink: /experience/
description: 
nav: true
nav_order: 4
#display_categories: [R, R]
horizontal: true
---

> <font size="2">Neural Networks and Deep Learning</font>
 



<!-- pages/projects 
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
   A few of my class projects from several courses during my Master's program at URI     
 
  {% for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  
   Generate cards for each project 
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

{% else %}/

 Display projects without categories 

{% assign sorted_projects = site.projects | sort: "importance" %}

   Generate cards for each project

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
</div> -->


[def]: prof_pic.jpg