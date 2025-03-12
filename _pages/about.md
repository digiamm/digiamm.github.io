---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a postdoctoral researcher at Sapienza University of Rome, where I completed my PhD in January 2024 under the supervision of [Prof. Giorgio Grisetti](https://sites.google.com/dis.uniroma1.it/grisetti/home). My research focuses on advancing SLAM and 3D reconstruction algorithms combining model-based and learning techniques. I am particularly interested in integrating/extracting semantic cues while exploring active perception for better autonomous navigation. My work spans from higher mathematical theories to practical data structure design, aiming to improve how autonomous systems perceive and interact with their environment.

News
======
  <ul>{% for post in site.news reversed %}
    {% include archive-news.html %}
  {% endfor %}</ul>
