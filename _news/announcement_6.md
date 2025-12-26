---
layout: post
title: We were present at the III Graduate Symposium, organized by the Faculty of Physical and Mathematical Sciences at the University of Chile
date: 2025-08-29 16:00:00-0400
inline: false
related_posts: false
---

Last Friday, on August 29, Shape Vision Lab had the pleasure of being part of the [III Graduate Symposium, organized by the Faculty of Physical and Mathematical Sciences at the University of Chile](https://ingenieria.uchile.cl/postgrados/simposio-postgrado/presentacion). 🎓✨

This event is all about creating networking opportunities for graduate students and showcasing their exciting research and progress to the community.

<img src="/assets/img/news/photo_2025-09-01_10-09-20.jpg" alt="Shape Vision Lab" style="width:100%; margin-top:15px; margin-bottom:15px;" />

👏 Huge thanks to Joaquín Cruz, Isaac Aguirre, Vicente Hidalgo, and Nicolás Caytuiro for proudly representing ShapeVision!

---

## **Research highlights**

### Joaquín Cruz (MSc): *Neural methods for repairing point clouds using cross-attention between points and restoration from noise.*

This proprosal explores **digital repair of archaeological objects using point clouds**, which are widely available and compatible with archaeological digitization. Novel neural network architectures inspired by **PointAttN** and **Convolutional Occupancy Networks** are being introduced, proposing three main approaches:

- **PointAttNB & DualConvONet:** classify noise to guide repairs.
- **PointAttNA:** transform noise entirely into complete reconstructions.
- **PointAttND:** apply PointAttN directly as a repair model.
- Additionally, an intermediate repair patch strategy was tested to preserve more of the original geometry.

The proposed models outperformed state-of-the-art methods like PCDiff and DRDAP in key metrics such as Chamfer Distance, with PointAttND achieving the strongest performance. Results highlight that combining attention mechanisms and noise modeling can effectively reconstruct point clouds of broken artifacts.

While challenges remain with complex geometries and limited dataset diversity, this research lays a solid foundation for future studies in digital repair of archaeological objects using only point cloud data.

### Isaac Aguirre (MSc): *Leveraging visual features extracted from 3D object renders to tackle geometric problems.*

By using *descriptors* —numerical vectors that capture geometry, patterns, and textures— AI can detect symmetries in 3D shapes much like humans perceive them visually.
Isaac's work builds upon **Feature Backprojection (FBP)**, a method in which images are captured around a 3D object, processed through a neural network to extract descriptors, and then projected back onto the object’s surface.
He proposes improvements to FBP, such as more uniform image sampling and rotational augmentation, resulting in more robust descriptors for detecting planar and axial symmetries, even when objects are rotated, noisy, or partially missing.
Preliminary results are competitive with state-of-the-art methods, highlighting the potential of this approach for applications such as archaeological artifact analysis, reconstruction, and 3D object segmentation.

### Vicente Hidalgo (MSc): *Exploring unsupervised video summarization to make 3D reconstruction from images more efficient.*

This research explores how **3D reconstruction from videos** can be improved through smarter selection of keyframes. In uncontrolled contexts—such as home recordings with unstable motion, varying speeds, and lighting changes—traditional uniform or random sampling often selects suboptimal frames.

The study proposes the use of unsupervised video summarization techniques, specifically sparse coding, to automatically identify the most representative keyframes. The methodology includes three phases:

- Validating the summarization technique against standard datasets with human annotations.
- Applying modern 3D reconstruction methods such as **Instant Neural Graphics Primitives (InstantNGP)** to generate models from the selected frames.
- Testing with real-world home videos to assess robustness under non-ideal conditions.

The expected results support the hypothesis that **unsupervised video summarization leads to more accurate and robust 3D reconstructions** compared to classical approaches. This work opens the possibility of generating high-fidelity 3D models from everyday videos captured by non-experts using common cameras.

### Nicolás Caytuiro (PhD): *Investigating how generative models for 3D data can explicitly incorporate structural priors.*

This work proposes a novel approach: **training generative models on partial structures (half-objects)**. The hypothesis is that if a model learns from half-objects within a sufficiently rich dataset, it can generate diverse and novel partial shapes which, when reflected, results in complete objects that are both visually plausible and geometrically symmetric.

To evaluate this, a **symmetry measurement protocol** was introduced. A generative model based on diffusion (Point-Voxel Diffusion (PVD)) was trained from scratch using a new half-object dataset derived from ShapeNet.

Results show that this methodology successfully promotes symmetry preservation during generation, producing high-quality, symmetric 3D objects and opening new directions for symmetry-aware generative modeling.

---

We are proud of our students’ contributions and excited to keep pushing the boundaries of 3D vision, AI, and geometry processing. 🚀
