---
layout: default
title: Projects
permalink: /projects/
---

<h1 class="page-title">Projects</h1>

<p class="lead">Selected research, academic, and engineering projects drawn from my CV and thesis-related materials.</p>

<section class="section">
  <h2>Research Projects</h2>
  <div class="grid grid--two">
    <article class="card project-card">
      <div>
        <h3>Gaussian-Based UAV SLAM With Novel Scene Representations</h3>
        <p class="project-card__meta">Thesis work / Sep 2023 - Present</p>
      </div>
      <p>Developing a SLAM approach that uses learned depth and optical-flow priors, neural scene representations, submap memory control, and rendered novel views to improve relocalization on resource-constrained UAV platforms.</p>
      <ul class="tag-list">
        <li>Visual SLAM</li>
        <li>3DGS</li>
        <li>Depth Priors</li>
        <li>Loop Closure</li>
      </ul>
    </article>
    <article class="card project-card">
      <div>
        <h3>FFS-SLAM</h3>
        <p class="project-card__meta">Under-review manuscript</p>
      </div>
      <p>Feed-Forward-Enhanced Submap Gaussian SLAM for large-scale RGB-only UAV mapping. The system decouples tracking from rendering, aligns feed-forward depth priors to stabilize scale, and streams inactive Gaussian submaps to CPU memory.</p>
      <ul class="tag-list">
        <li>Monocular SLAM</li>
        <li>UAV Mapping</li>
        <li>PyTorch</li>
        <li>FAISS</li>
      </ul>
    </article>
  </div>
</section>

<section class="section">
  <h2>Industry Experience</h2>
  <article class="card project-card">
    <div>
      <h3>COLMAP Optimization for Efficient 3D Reconstruction</h3>
      <p class="project-card__meta">Internship / Xi'an, China / Oct 2025 - Present</p>
    </div>
    <p>Optimizing a 3D reconstruction pipeline to reduce the time needed to build Gaussian Splatting-based 3D scenes. The work includes handheld scanning device integration, ROS-related testing, and COLMAP parameter tuning on collected video datasets.</p>
    <ul class="tag-list">
      <li>COLMAP</li>
      <li>Gaussian Splatting</li>
      <li>ROS</li>
      <li>3D Reconstruction</li>
    </ul>
  </article>
</section>

<section class="section">
  <h2>Academic Projects</h2>
  <div class="grid grid--two">
    <article class="card project-card">
      <h3>Monocular 2D-to-3D Content Pipeline for VR</h3>
      <p>Built a pipeline that converts single images, prerecorded videos, and live camera streams into stereo content for head-mounted displays using dense depth prediction, OpenGL warping, and inpainting for missing pixels.</p>
      <ul class="tag-list">
        <li>Depth Estimation</li>
        <li>OpenGL</li>
        <li>ProPainter</li>
        <li>VR</li>
      </ul>
    </article>
    <article class="card project-card">
      <h3>Visual Odometry on KITTI</h3>
      <p>Led a visual odometry pipeline for vehicle motion tracking from consecutive camera frames using ORB features, KLT optical-flow tracking, and a PnP pose solver in OpenCV.</p>
      <ul class="tag-list">
        <li>OpenCV</li>
        <li>ORB</li>
        <li>KLT</li>
        <li>PnP</li>
      </ul>
    </article>
    <article class="card project-card">
      <h3>Cityscape Modeling From Drone Capture</h3>
      <p>Built 3D city models from UE4/AirSim simulated drone flights and replicated the workflow on real NWPU campus flights using photogrammetry and Cesium visualization.</p>
      <ul class="tag-list">
        <li>AirSim</li>
        <li>UE4</li>
        <li>Photogrammetry</li>
        <li>Cesium</li>
      </ul>
    </article>
    <article class="card project-card">
      <h3>Wearable Technologies for Sports Healthcare</h3>
      <p>Built a smartphone-sensor activity-recognition demo to visualize activity predictions and support sports healthcare use cases.</p>
      <ul class="tag-list">
        <li>Python</li>
        <li>TensorFlow Lite</li>
        <li>Streamlit</li>
        <li>Mobile Sensors</li>
      </ul>
    </article>
  </div>
</section>
