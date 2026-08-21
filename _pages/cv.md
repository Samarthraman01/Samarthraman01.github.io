---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF](/files/CV.pdf)

---

## Education

**M.Sc. Electromobility Engineering**
Friedrich-Alexander University (FAU), Erlangen-Nürnberg, Germany
*October 2022 – June 2026*
Thesis: Sensor Selection and Positioning Analysis for Medical Robotics

**B.Tech. Mechanical Engineering**
PES University, Bengaluru, India
*August 2017 – August 2021*

---

## Work Experience

**Research Assistant | Working Student**
Siemens Healthineers, Erlangen, Germany
*February 2025 – Present*

- Built a multi-sensor perception pipeline integrating LiDAR, RGB-D, and camera streams under real-time constraints across 3 sensor modalities
- Designed a Kalman filter-based multi-object tracking system improving trajectory prediction consistency by ~40%
- Developed deterministic C++ components for synchronized data acquisition cutting pipeline latency by ~30%

*Hospital Digital Twin and Real-to-Sim Research*

- Collaborated with Uniklinikum radiologists to translate clinical workflow requirements into simulation constraints for robotic sensor placement
- Integrated high-level robotic decision logic with low-level perception outputs in a safety-critical environment
- Developed benchmarking frameworks to validate perception robustness across sensor configurations

*Master Thesis: Sensor Selection and Positioning Analysis for Medical Robotics*
*June 2025 – November 2025*

- Built a high-fidelity Unity-based hospital digital twin to simulate and compare robotic sensor configurations across realistic clinical layouts
- Implemented synchronized simulation of RGB, depth, and 3D LiDAR sensors modeling occlusions, noise, and range limitations
- Integrated Unity with ROS 2 to record time-aligned multimodal sensor data feeding into downstream perception pipelines
- Conducted structured sensor placement studies across 6+ layout configurations with quantitative trade-off analyses

---

**Research Assistant**
Institute for Factory Automation and Production Systems (FAPS), FAU, Erlangen, Germany
*July 2024 – February 2025*

- Developed a Unity-based VR simulator for assistive robotics covering full design, implementation, and testing cycles
- Implemented interaction logic, movement systems, and visualization pipelines within Unity
- Integrated research into assistive robotics with applications toward medical device navigation

---

**New Product Development Engineer**
SAA AB Engineering Pvt Ltd, Bengaluru, India
*September 2021 – July 2022*

---

## Projects

**EgoSeg-RT** [GitHub](https://github.com/Samarthraman01/EgoSeg-RT)

- Systematic deployment characterization of real-time semantic segmentation on egocentric first-person video
- Benchmarked SegFormer-B0 and B2 across PyTorch, ONNX FP32, and INT8 on CPU, MPS, and T4 GPU
- Quantified domain shift from ADE20K (mIoU 0.350) to VISOR-HOS egocentric footage (IoU 0.000)
- Identified SegFormer-B0 as the only variant achieving real-time throughput (79.4 FPS on T4, 21.1 FPS on M2 MPS)

**SemanticBot** [GitHub](https://github.com/Samarthraman01/Semanticbot)

- End-to-end ROS 2 Humble pipeline integrating YOLO-World and OpenAI CLIP for open-vocabulary semantic 3D mapping
- C++ ROS 2 fusion node with pinhole projection and SE(3) transforms publishing PointCloud2 in real time
- Produced a semantic map of 688 classified objects queryable by natural language

**MediSeg** [GitHub](https://github.com/Samarthraman01/MediSeg)

- Semantic segmentation built from scratch in PyTorch on ADE20K (150 classes)
- Implemented U-Net and SegFormer architectures with full ONNX export and INT8 quantization pipeline

---

## Publication

M. Kalenberg, M. Heine, **S. R. Ghanate**, C. Hofmann, J. Franke, J. Walter, J. Fuerst,
*"Social Force-Based Proxemics for Mutual and Comfortable Navigation of an Intelligent Wheelchair,"*
IEEE International Conference on Advanced Robotics and its Social Impact (ARSO 2026), Vienna, Austria, June 2026.
[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11536118)

---

## Skills

**Computer Vision and AI**
YOLO-World, CLIP, SegFormer, U-Net, PyTorch, TensorFlow, Semantic Segmentation, Open-Vocabulary Detection, Vision-Language Models

**Sensor Integration**
LiDAR, RGB-D, Depth Cameras, Multi-Sensor Fusion, Point Cloud Processing (Open3D)

**Robotics and Middleware**
ROS 2 Humble, RViz2, RTAB-Map, Gazebo

**Simulation and Digital Twin**
Unity3D, Unity-ROS 2 Bridge, Meta Quest 2 / XR

**Programming**
C++17, Python, C#, YAML, Git

**Environment**
Linux (Ubuntu 22.04 ARM64), Docker, Visual Studio Code

---

## Languages

- English — C1 (Professional working proficiency)
- German — B1 (currently improving)
