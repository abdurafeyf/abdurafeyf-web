---
title: >-
  VolumeVision: A 2.5D Hierarchical Architecture for Efficient Automated
  Reporting of Chest CT Volumes
slug: volume-vision
description: CT-RATE
tags:
  - technical
  - learning
added: 2025-07-15T19:00:00.000Z
---

[See paper here](https://assets.tina.io/1fb09d03-9237-4c49-aaa9-d024a83c7ac7/VolumeVision.pdf)

# Abstract

Automated radiology report generation from 3D chest CT volumes remains challenging due to computational complexity and the need for clinically accurate narratives. We present VolumeVision, a novel framework that combines intelligent slice selection with MedGemma 4B for efficient 3D CT report generation. Our approach uses a learned slice selector to identify the most diagnostically relevant views from axial, coronal, and sagittal planes, followed by crossmodal fusion with a medical vision-language model. Experiments on a curated subset of 5,000 C T-RATE studies demonstrate that VolumeVision achieves decent performance compared to existing methods while requiring significantly fewer computational resources. Our hierarchical 2.5D approach offers a practical solution for automated radiology reporting in clinical settings.