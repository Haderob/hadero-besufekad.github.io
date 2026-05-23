---
layout: default
title: Research
permalink: /research/
---

<h1 class="page-title">Research</h1>

<p class="lead">My research centers on visual SLAM and robot perception for complex, unstructured environments. I combine classical geometric methods with learning-based depth, pose, and scene representation models to improve dense mapping, relocalization, and scalable 3D understanding.</p>

<section class="section">
  <h2>Master's Thesis</h2>
  <div class="panel">
    <h3>Research on UAV SLAM Based on Novel Scene Representations</h3>
    <p>My thesis, titled <em>Research on UAV SLAM Based on Novel Scene Representations</em>, studies how modern scene representations can improve drone SLAM. The work introduces learned perception modules and neural scene representations to strengthen relocalization, reduce drift, and maintain scalable maps on resource-constrained platforms.</p>
    <ul>
      <li>Uses learned depth and optical-flow priors for geometry estimation from monocular video.</li>
      <li>Partitions global maps into bounded submaps so memory remains controlled over long trajectories.</li>
      <li>Uses global visual descriptors, neural retrieval, geometric verification, and pose-graph optimization for loop closure.</li>
      <li>Explores novel-view rendering and Gaussian representations for relocalization and dense reconstruction.</li>
    </ul>
  </div>
</section>

<section class="section">
  <h2>Research Themes</h2>
  <div class="grid grid--two">
    <article class="card">
      <h3>3D Gaussian Splatting for SLAM</h3>
      <p>3D Gaussian Splatting provides an explicit, differentiable representation with high-quality real-time rendering. I study how to adapt it for SLAM through submaps, active-region management, duplicate pruning, and memory-aware optimization.</p>
    </article>
    <article class="card">
      <h3>Feed-Forward Monocular Geometry</h3>
      <p>Feed-forward depth, pose, and correspondence models can reduce the need for slow iterative optimization. I am interested in combining these predictions with geometric verification and SLAM back-ends.</p>
    </article>
    <article class="card">
      <h3>Robust UAV Mapping</h3>
      <p>Outdoor UAV trajectories can span large areas and suffer from low parallax, texture-poor regions, motion blur, and scale drift. My work targets dense RGB-only mapping under these constraints.</p>
    </article>
    <article class="card">
      <h3>Multimodal and Embodied Perception</h3>
      <p>I am interested in how robust 3D world models can support navigation, motion generation, and higher-level decision-making, including future work on multimodal and Vision-Language-Action systems.</p>
    </article>
  </div>
</section>

<section class="section">
  <h2>Current Direction</h2>
  <div class="panel">
    <p>I am actively seeking PhD opportunities for Fall 2026 in robot perception, visual SLAM, 3D vision, embodied intelligence, and related areas. I am especially interested in research that connects robust real-time 3D perception with decision-making in physical systems.</p>
  </div>
</section>
