---
title: "MD-SLAM: Multi-cue Direct SLAM"
collection: publications
permalink: /publication/2022-md-slam
# excerpt: ''
date: 2022-10-23
venue: 'International Conference on Intelligent Robots and Systems (IROS) (just accepted)'
authors: '<b>Luca Di Giammarino</b>, Leonardo Brizi, Tiziano Guadagnino, Cyrill Stachniss, Giorgio Grisetti'
teaser: /pub/di2022md.gif
arxiv: 'https://arxiv.org/abs/2203.13237'
# code: ''
categories: [slam]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/pub/di2022md.gif" alt="Teaser Image" title="teaser" />

## Abstract

> Simultaneous Localization and Mapping (SLAM) systems are fundamental building blocks for any autonomous robot navigating in unknown environments. The SLAM implementation heavily depends on the sensor modality employed on the mobile platform. For this reason, assumptions on the scene's structure are often made to maximize estimation accuracy. This paper presents a novel direct 3D SLAM pipeline that works independently for RGB-D and LiDAR sensors. Building upon prior work on multi-cue photometric frame-to-frame alignment, our proposed approach provides an easy-to-extend and generic SLAM system. Our pipeline requires only minor adaptations within the projection model to handle different sensor modalities. We couple a position tracking system with an appearance-based relocalization mechanism that handles large loop closures. Loop closures are validated by the same direct registration algorithm used for odometry estimation. We present comparative experiments with state-of-the-art approaches on publicly available benchmarks using RGB-D cameras and 3D LiDARs. Our system performs well in heterogeneous datasets compared to other sensor-specific methods while making no assumptions about the environment. Finally, we release an open-source C++ implementation of our system.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
    @article{di2022md,
    title={MD-SLAM: Multi-cue Direct SLAM},
    author={Di Giammarino, Luca and Brizi, Leonardo and Guadagnino, Tiziano and Stachniss, Cyrill and Grisetti, Giorgio},
    journal={arXiv preprint arXiv:2203.13237},
    year={2022}
    }