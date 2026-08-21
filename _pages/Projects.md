---
layout: archive
title: "Projects"
permalink: /Projects/
author_profile: true
---

All my projects are independent research and engineering work 
focused on building perception systems that run on real hardware. 
The common thread: take a model, understand it deeply, deploy it, 
and measure what actually happens.

---

## EgoSeg-RT
[GitHub](https://github.com/Samarthraman01/EgoSeg-RT)

Most segmentation research stops at benchmark numbers. This project 
asks what happens when you actually deploy these models on a wearable 
camera. I trained SegFormer on standard indoor data and ran it on 
real egocentric kitchen footage the model completely failed, 
predicting "building exterior" for a kitchen sink. The project 
systematically characterizes where, why, and how much performance 
drops across different hardware and export formats.

---

## SemanticBot
[GitHub](https://github.com/Samarthraman01/Semanticbot)

A robot that understands its environment through language. The idea 
was simple: instead of training a model for every object category, 
use vision-language models to detect and classify anything, lift the 
detections into 3D space, and let you query the result in natural 
language. Built with ROS 2 and C++ so it actually runs in real time 
on a robot.

---

## MediSeg
[GitHub](https://github.com/Samarthraman01/MediSeg)

Built semantic segmentation from scratch in PyTorch to understand 
how these models work, not just how to use them. Implemented U-Net 
and SegFormer, trained on ADE20K, and exported to ONNX with INT8 
quantization — shrinking the model from 105MB to 29MB with less 
than 2% accuracy loss.
