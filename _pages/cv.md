---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Data Science, The University of Hong Kong, Hong Kong SAR (2024 - 2028 Expected) 
  * Funded by the **Hong Kong PhD Fellowship Scheme**
  * Also recognized as **HKU Presidential PhD Scholar**
* Bachelor of Science in Information and Computing Science, Peking University, Beijing, China (2020 - 2024)  


Work experience
======
* June 2023 - November 2023: Research Assistant
  * HKU Musketeers Foundation Institute of Data Science, The University of Hong Kong, Hong Kong SAR
  * Duties includes: (1) Developed machine learning algorithms for robotic manipulation tasks. (2) Designed methods for robots to learn task-relevant concepts from unlabeled demonstrations. (3) Created frameworks for discovering and utilizing manipulation primitives.
  * Supervisor: Prof. Yanchao Yang
  
Skills
======
* **Machine Learning & AI PyTorch**: JAX, TensorFlow, etc.
* **Programming Languages Python**: C/C++, CUDA, Arduino, etc.
* **Development Tools Git/GitHub**: Docker, Weights & Biases, etc.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
