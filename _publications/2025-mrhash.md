---
title: "Resolution Where It Counts: Hash-based GPU-Accelerated 3D Reconstruction via Variance-Adaptive Voxel Grids"
collection: publications
permalink: /publication/2025-mrhash
# excerpt: ''
date: 2025-01-01
venue: "ACM Transactions on Graphics (TOG)"
authors: "Lorenzo De Rebotti, Emanuele Giacomini, Giorgio Grisetti, <b>Luca Di Giammarino</b>"
teaser: /pub/derebotti2025mrhash.png
arxiv: "https://arxiv.org/abs/2511.21459"
github: "https://github.com/rvp-group/mrhash"
paper: "https://dl.acm.org/doi/10.1145/3777909"
project: "https://rvp-group.github.io/mrhash/"
# code: ''
categories: [3d-reconstruction, gpu, tsdf, gaussian-splatting]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/pub/derebotti2025mrhash.gif" alt="Teaser Image" title="teaser" />

## Abstract

> Efficient and scalable 3D surface reconstruction from range data remains a core challenge in computer graphics and vision, particularly in real-time and resource-constrained scenarios. Traditional volumetric methods based on fixed-resolution voxel grids or hierarchical structures like octrees often suffer from memory inefficiency, computational overhead, and a lack of GPU support. We propose a novel variance-adaptive, multi-resolution voxel grid that dynamically adjusts voxel size based on the local variance of signed distance field (SDF) observations. Unlike prior multi-resolution approaches that rely on recursive octree structures, our method leverages a flat spatial hash table to store all voxel blocks, supporting constant-time access and full GPU parallelism. This design enables high memory efficiency, and real-time scalability. We further demonstrate how our representation supports GPU-accelerated rendering through a parallel quad-tree structure for Gaussian Splatting, enabling effective control over splat density. Our open-source CUDA/C++ implementation achieves up to 13× speedup and 4× lower memory usage compared to fixed-resolution baselines, while maintaining on par results in terms of reconstruction accuracy, offering a practical and extensible solution for high-performance 3D reconstruction.

## Resources

<a href="https://arxiv.org/abs/2511.21459">[arxiv]</a> <a href="https://dl.acm.org/doi/10.1145/3777909">[paper]</a> <a href="https://rvp-group.github.io/mrhash/">[project page]</a> <a href="https://github.com/rvp-group/mrhash">[code]</a>

## Bibtex
@article{10.1145/3777909,
  author = {De Rebotti, Lorenzo and Giacomini, Emanuele and Grisetti, Giorgio and Di Giammarino, Luca},
  title = {Resolution Where It Counts: Hash-based GPU-Accelerated 3D Reconstruction via Variance-Adaptive Voxel Grids},
  year = {2025},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  issn = {0730-0301},
  url = {https://doi.org/10.1145/3777909},
  doi = {10.1145/3777909},
  journal = {ACM Trans. Graph.},
  keywords = {Surface Reconstruction, Novel View Synthesis, Gaussian Splatting}
}
