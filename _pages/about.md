---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I recently finished my M.Sc. in Electromobility Engineering at FAU 
Erlangen-Nürnberg. During my studies I worked as a Research Assistant 
at Siemens Healthineers, building perception systems for clinical 
environments. My thesis looked at sensor selection and placement for 
medical robotics — specifically, how to use a Unity-based hospital 
digital twin to evaluate sensor configurations before touching real 
hardware.

I like working on things that actually run. Not demos, not notebooks — 
systems that process real sensor data, make decisions in real time, and 
fail in ways you have to debug. Most of my work sits somewhere between 
making machines see the world and making that vision run fast enough 
to be useful.

---

## Research Interests

- Real-time semantic segmentation and domain adaptation
- Multi-sensor fusion — LiDAR, RGB-D, and camera
- Egocentric perception for wearable systems
- Deployment-aware deep learning — ONNX, TensorRT, ROS 2 C++
- Robust perception in safety-critical robotic environments
- Medical imaging AI and healthcare perception systems

---

## Work

**Siemens Healthineers** — Research Assistant (02/2025 – Present)

- Built a multi-sensor pipeline integrating LiDAR, RGB-D, and camera 
  streams under real-time constraints across 3 sensor modalities
- Built high-fidelity digital twins of complex hospital environments 
  such as catheter labs and operating rooms for robotic simulation 
  and sensor placement evaluation
- Bridged real-to-sim pipelines by integrating Unity with ROS 2, 
  enabling time-aligned multimodal sensor data to feed directly into 
  downstream perception and robotics workflows

**FAPS, FAU Erlangen-Nürnberg** — Research Assistant (07/2024 – 02/2025)

- Developed a Unity-based VR simulator for assistive robotics, 
  covering full design, implementation, and testing cycles

---

## Projects

**EgoSeg-RT** — [GitHub](https://github.com/Samarthraman01/EgoSeg-RT)  
Studied how well semantic segmentation models hold up when deployed 
on real wearable camera footage. Tested SegFormer across hardware and 
export formats, and found that models trained on standard indoor 
datasets completely fail on egocentric kitchen video. A useful reminder 
that benchmark numbers and deployment reality are very different things.

**SemanticBot** — [GitHub](https://github.com/Samarthraman01/Semanticbot)  
Built a robot that understands its environment through language. 
Detects and identifies objects using vision-language models, lifts 
them into 3D space, and lets you query the map in natural language — 
running in real time with ROS 2 and C++.

**MediSeg** — [GitHub](https://github.com/Samarthraman01/MediSeg)  
Built semantic segmentation from scratch in PyTorch to understand how 
these models actually work. Trained U-Net and SegFormer on ADE20K and 
exported to ONNX for portable deployment.

---

## Publication

M. Kalenberg, M. Heine, **S. R. Ghanate**, C. Hofmann, J. Franke, 
J. Walter, J. Fuerst,  
*"Social Force-Based Proxemics for Mutual and Comfortable Navigation 
of an Intelligent Wheelchair,"*  
IEEE ARSO 2026, Vienna, Austria, June 2026.  
[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11536118)

---

## Education

- **M.Sc. Electromobility Engineering** — FAU Erlangen-Nürnberg (2022 – 2026)
- **B.Tech. Mechanical Engineering** — PES University, Bengaluru (2017 – 2021)

---

## Skills

**Computer Vision & AI:** YOLO-World, CLIP, SegFormer, U-Net, PyTorch, 
TensorFlow, Semantic Segmentation, Open-Vocabulary Detection  
**Sensor Integration:** LiDAR, RGB-D, Depth Cameras, Multi-Sensor 
Fusion, Point Cloud Processing (Open3D)  
**Robotics & Middleware:** ROS 2 Humble, RViz2, RTAB-Map, Gazebo  
**Simulation:** Unity3D, Unity-ROS 2 Bridge, Meta Quest 2 / XR  
**Programming:** C++17, Python, C#, YAML, Git  
**Environment:** Linux (Ubuntu 22.04 ARM64), Docker, Visual Studio Code

---

## Languages

- English — C1
- German — B1

---

I am currently looking for PhD positions and research collaborations 
in computer vision, robotics, and perception systems.  
Reach me at samarthramanghanate@gmail.com