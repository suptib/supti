---
layout: page
title: Experience 
permalink: /experience/
description: A few of my master's coursework projects 
nav: true
nav_order: 4
#display_categories: [R, R]
horizontal: true
---

---
**<font size="3"><mark>Analyzing EEG Brainwaves to Decode
Attentional State for Faces and Scenes</mark></font>**  
 - <font size="2">Developed a Multilayer Perceptron model for EEG signal classification using TensorFlow's Keras API. Trained over 50 epochs with a batch size of 32 and a 20 validation split using Adam optimizer and categorical cross entropy loss function.</font> 

---
  [**<font size="3"><mark>Multivariate Statistical Methods</mark></font>**](https://github.com/suptib/Multivariate-Methods-on-Wine-Data)
  - <font size="2">Applied Multidimensional Scaling (MDS) for visualization,similarity or dissimilarity between data points (R Packages: MASS, smacof)  

    Discriminant Analysis(LDA/QDA) to classify observations into predefined categories (R Package: MASS)  
  
    Principal Component Analysis (PCA) to reduce dimensionality, visualize data in lower dimensions while preserving variance (R Packages: stats, FactoMineR, factoextra)</font> 
    
---
  [**<font size="3"><mark>Applied Regression Analysis</mark></font>**](https://github.com/suptib/Applied-Regression-Analysis)
  - <font size="2">Applied Ridge Regression to perform variable selection (R Package:'glmnet')  

    Cox Proportional Hazards Regression for modeling the time to thyroid cancer onset as a function of TSH levels and radiation exposure (R Package: survival)

    Logistic Regression to find the probability of thyroid disease as a function of TSH levels, age, and family history (R Package: thyroid, glm() with family=binomial)</font>

---





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