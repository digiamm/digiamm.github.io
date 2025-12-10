---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Professor at Sapienza University of Rome, where I also completed my PhD under the supervision of [Prof. Giorgio Grisetti](https://sites.google.com/dis.uniroma1.it/grisetti/home). My research focuses on SLAM, 3D reconstruction, and active perception, combining model-based optimization with learning-driven techniques to advance robust multimodal perception.

I work on vision systems, developing methods for odometry, bundle adjustment, multimodal calibration, and active viewpoint selection. My recent efforts explore Gaussian scene representations, continuous-time SLAM, and efficient GPU-accelerated 3D mapping. Beyond academia, I am a cofounder of [Z-up](https://www.zedup.it/), a startup dedicated to bringing advanced robotic perception and simulation technologies into real-world applications.

News
======
  <ul>{% for post in site.news reversed %}
    {% include archive-news.html %}
  {% endfor %}</ul>
