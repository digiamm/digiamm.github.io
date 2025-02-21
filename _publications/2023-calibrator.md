---
title: "Ca2Lib: Simple and Accurate LiDAR-RGB Calibration using Small Common Markers"
collection: publications
permalink: /publication/2023-calibration
# excerpt: ''
date: 2023-09-14
venue: 'Sensors'
# venue: 'International Conference on Intelligent Robots and Systems (IROS) (just accepted)'
authors: 'Emanuele Giacomini*, Leonardo Brizi*, <b>Luca Di Giammarino</b>, Omar Salem, Giorgio Grisetti'
teaser: /pub/giacomini2023calib.png
arxiv: 'https://arxiv.org/pdf/2309.07874v1.pdf'
github: 'https://github.com/rvp-group/ca2lib'
# code: ''
categories: [calibration]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/pub/giacomini2023calib.png" alt="Teaser Image" title="teaser" />


## Abstract

> In many fields of robotics, knowing the relative position and orientation between two sensors is a mandatory precondition to operate with multiple sensing modalities. In this context, the pair LiDAR-RGB cameras offer complementary features: LiDARs yield sparse high quality range measurements, while RGB cameras provide a dense color measurement of the environment. Existing techniques often rely either on complex calibration targets that are expensive to obtain, or extracted virtual correspondences that can hinder the estimate’s accuracy. In this paper we address the problem of LiDAR-RGB calibration using typical calibration patterns (i.e. A3 chessboard) with minimal human intervention. Our approach exploits the planarity of the target to find correspondences between the sensors measurements, leading to features that are robust to LiDAR noise. Moreover, we estimate a solution by solving a joint non-linear optimization problem. We validated our approach by carrying on quantitative and comparative experiments with other state-of-the-art approaches. Our results show that our simple schema performs on par or better than other approaches using complex calibration targets. Finally, we release an open-source C++ implementation.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
  @article{giacomini2024ca2lib,
  title={Ca2lib: Simple and accurate lidar-rgb calibration using small common markers},
  author={Giacomini, Emanuele and Brizi, Leonardo and Di Giammarino, Luca and Salem, Omar and Perugini, Patrizio and Grisetti, Giorgio},
  journal={Sensors},
  volume={24},
  number={3},
  pages={956},
  year={2024},
  publisher={MDPI}
}