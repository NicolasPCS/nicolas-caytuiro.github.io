---
layout: post
title: Joaquín Cruz's MSc Thesis Defense
date: 2025-09-01 16:00:00-0400
inline: false
related_posts: false
---

**Topic:** *Digital Repair of Archaeological Objects Using Cross-Attention and Noise on Point Clouds*

---

**Abstract:** In the current digital era, 3D modeling techniques have enabled significant advances in archaeology, a discipline that seeks to understand the human past through the study and preservation of ancient remains. However, many digitized archaeological objects exhibit incomplete geometries due to the deterioration of the originals or limitations in scanning methods. Recent progress has been made in digital repair of incomplete objects. Yet, many existing approaches are not directly applicable to archaeological artifacts, since they often assume properties such as closed surfaces, or simply lose details when the goal is to preserve as much of the original geometry as possible. To address this, we focus on point clouds, given the ease of acquiring this type of data and their compatibility with digitized archaeological objects.

In this thesis, we address the problem of digitally repairing archaeological objects represented as point clouds. We propose new neural network architectures inspired by previous models such as PointAttN and Convolutional Occupancy Networks. Specifically, we explore three main approaches: noise classification to generate repairs (PointAttNB and DualConvONet), a variant that transforms all noise into complete repairs (PointAttNA), and the direct use of PointAttN as a repair network for archaeological objects (PointAttND). We also experiment with generating intermediate repair patches, which, when concatenated with the fractured input, produce repaired objects that retain points from the original artifact.

We show that the proposed models are effective in the digital repair of archaeological objects, outperforming state-of-the-art methods such as PCDiff and DRDAP on key metrics like the Chamfer Distance Factor. In particular, PointAttND achieved the best overall results, while PointAttNA and PointAttNB also reached competitive performance on several evaluation metrics. Our results demonstrate that combining attention mechanisms with noise can effectively produce point cloud reconstructions of repaired objects. Although challenges remain when dealing with complex geometries and the limited diversity of training datasets, our contributions establish a solid foundation for future research, highlighting the potential of these techniques to repair archaeological objects using only their point clouds.

The implementation of the models is available at: [Cubolink/PointNoiseAttentionRepairer](https://github.com/Cubolink/PointNoiseAttentionRepairer)

---

#### Details

<ul>
    <li><b>Advisor</b>: Ivan Sipiran</li>
    <li><b>Room</b>: Picarte Auditorium</li>
    <li><b>Date</b>: Monday, September 1st at 14:00 PM</li>
</ul>