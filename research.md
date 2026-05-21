---
layout: default
title: Research
---

# Research

My research bridges **classical geometric SLAM** and **modern neural scene representations** to build robust, scalable perception systems for autonomous robots and vehicles. I am particularly interested in closing the gap between high-fidelity generative mapping and real-time feed-forward inference.

## Current Focus

### Safety-Aware Feed-Forward Monocular SLAM

My master's thesis work focuses on developing a **Gaussian-based monocular SLAM framework** that:

- Injects **learned depth priors** for metric-scale stability
- Partitions global maps into **bounded-memory submaps** for real-time performance on constrained hardware
- Integrates **feed-forward depth and pose networks** (VGGT, DUSt3R) to reduce initialization bottlenecks
- Targets **30 fps** operation through lightweight, decoupled geometry and appearance updates

### Research Themes

**1. Real-Time 3D Gaussian Splatting for SLAM**

3D Gaussian Splatting (3DGS) offers an explicit, differentiable scene representation that maintains the visual fidelity of NeRFs while enabling direct rendering. I investigate how to make 3DGS-based SLAM truly real-time and robust on standard robotic hardware, including submap partitioning, active-region management, and memory compression.

**2. Feed-Forward Perception for Geometry**

Feed-forward models such as DUSt3R, MASt3R, and VGGT achieve real-time depth and pose estimation without costly iterative optimization. I study how to fuse these predictions with generative mapping to obtain both speed and geometric fidelity.

**3. Robustness Under Challenging Conditions**

Real-world SLAM must survive illumination changes, dynamic motion, and scene appearance variation. My work explores:
- Illumination-invariant feature matching for day-night operation
- Dynamic-object masking via rendering residuals and optical-flow inconsistency
- Uncertainty-aware weighting to down-weight unreliable observations

**4. Multi-Sensor Fusion**

To resolve monocular scale ambiguity and improve reliability, I am interested in tightly coupling **LiDAR and IMU** with monocular+3DGS front ends through uncertainty-weighted factor graphs and online calibration.

## Long-Term Vision

I aim to advance monocular SLAM from "fast but fragile" to **fast, robust, and uncertainty-aware** — delivering dense, temporally consistent representations that enhance downstream state estimation, navigation, and safe decision-making in autonomous systems.

---

*I am actively seeking PhD opportunities for Fall 2026 to continue this research.*
