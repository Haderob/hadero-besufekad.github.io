---
layout: default
title: Projects
---

# Projects

## Research Projects

### Gaussian-Based Monocular SLAM Framework

My master's thesis project. I designed a complete SLAM system that combines 3D Gaussian Splatting with feed-forward depth priors for real-time, metric-scale mapping on resource-constrained platforms.

- **Tech**: Python, PyTorch, OpenCV, COLMAP, ROS2
- **Highlights**: Submap partitioning, neural retrieval for loop closure, novel-view rendering for relocalization
- **Status**: Ongoing thesis work

### FFS-SLAM: Feed-Forward-Enhanced Submap Gaussian SLAM

A collaborative research project building a feed-forward-guided tracking and mapping framework that achieves near-real-time performance by decoupling geometry and appearance updates.

- **Tech**: Python, PyTorch, CUDA
- **Collaborators**: Jia-Hao Liu, Tao Yang, Negaar Rezvanfar, Ke Ma
- **Status**: Under review

## Industry Experience

### COLMAP-to-3DGS Pipeline Optimization

**Square Star Technology**, Xi'an, China — *Oct 2025 – Present*

- Optimized a 3D reconstruction pipeline to significantly reduce the time required to build Gaussian Splatting-based 3D scenes
- Tested and integrated handheld scanning devices into the pipeline using ROS and Gaussian Splatting reconstruction
- Performed parameter tuning and optimization of COLMAP by collecting and analyzing causal video datasets

## Academic Projects

### Monocular 2D-to-3D Content Pipeline for VR

Built an end-to-end pipeline that turns single images, pre-recorded videos, and live camera streams into stereo content for head-mounted displays.

- **Tech**: PyTorch, OpenGL, ProPainter, ROS2
- **Role**: Team lead — designed pipeline, data collection, code review, fine-tuning
- **Highlights**: Dense depth prediction, OpenGL warping for right-eye view, inpainting for missing pixels

### Visual Odometry Pipeline on KITTI

Developed a complete visual odometry pipeline for 3D vehicle motion tracking using the KITTI driving dataset.

- **Tech**: Python, OpenCV
- **Methods**: ORB features, KLT optical-flow tracking, PnP pose solver
- **Outcome**: Stable 3D trajectories on real-world data

### Cityscape Modeling from Drone Capture

Built end-to-end 3D city models from UE4/AirSim simulated drone captures and replicated on real NWPU campus flights.

- **Tech**: Unreal Engine 4, AirSim, photogrammetry (MVG/MVS), Cesium
- **Outcome**: Interactive 3D city views from both simulated and real drone data

### Wearable Technologies for Sports Healthcare

Built a smartphone-sensor-based activity recognition demo showing how wearable data and AI can help prevent injuries and enhance performance.

- **Tech**: Python, TensorFlow Lite, Streamlit
- **Outcome**: Real-time web app for activity prediction and visualization

## Open Source & Tools

- Contributor to COLMAP optimization workflows
- Custom Gaussian Splatting submap management utilities
- Reproducible evaluation scripts for TUM RGB-D and KITTI benchmarks
