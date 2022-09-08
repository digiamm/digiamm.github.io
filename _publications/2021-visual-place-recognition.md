---
title: "Visual place recognition using LiDAR intensity information"
collection: publications
permalink: /publication/2021-visual-place-recognition
# excerpt: ''
date: 2021-9-27
venue: 'International Conference on Intelligent Robots and Systems (IROS)'
authors: '<b>Luca Di Giammarino</b>, Irvin Aloise, Cyrill Stachniss, Giorgio Grisetti'
teaser: /pub/di2021visual.png
arxiv: 'https://arxiv.org/abs/2103.09605'
# code: ''
categories: [vpr]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/pub/di2021visual.png" alt="Teaser Image" title="teaser" />

## Abstract

> Robots and autonomous systems need to know where they are within a map to navigate effectively. Thus, simultaneous localization and mapping or SLAM is a common building block of robot navigation systems. When building a map via a SLAM system, robots need to re-recognize places to find loop closure and reduce the odometry drift. Image-based place recognition received a lot of attention in computer vision, and in this work, we investigate how such approaches can be used for 3D LiDAR data. Recent LiDAR sensors produce high-resolution 3D scans in combination with comparably stable intensity measurements. Through a cylindrical projection, we can turn this information into a 360° panoramic range image. As a result, we can apply techniques from visual place recognition to LiDAR intensity data. The question of how well this approach works in practice has only partially been investigated. This paper provides an analysis of how such visual techniques can be with LiDAR data, and we provide an evaluation on different datasets. Our results suggest that this form of place recognition is possible and an effective means for determining loop closures.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
    @inproceedings{di2021visual,
    title={Visual place recognition using LiDAR intensity information},
    author={Di Giammarino, Luca and Aloise, Irvin and Stachniss, Cyrill and Grisetti, Giorgio},
    booktitle={2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
    pages={4382--4389},
    year={2021},
    organization={IEEE}
    }