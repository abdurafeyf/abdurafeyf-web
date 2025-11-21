---
title: >-
  Radixpert: A Multimodal Approach to Medical Imaging
slug: radixpert
description: Radiology Report Generation (2D)
tags:
  - technical
  - learning
  - work
added: 2025-05-29T19:00:00.000Z
---

[See paper here](https://assets.tina.io/1fb09d03-9237-4c49-aaa9-d024a83c7ac7/Radixpert_A_Multimodal_Approach_to_Medical_Imaging.pdf)

# Abstract

Automated radiology report generation (ARRG) has emerged as a critical application for improving clinical efficiency and reducing physician workload. However, existing models often suffer from hallucinations and spatial inaccuracies due to a lack of explicit anatomical grounding. This paper presents Radixpert, a novel anatomy-guided vision-language model that leverages explicit segmentation priors to enhance report generation accuracy. Unlike traditional end-to-end approaches, our framework adopts a highly efficient dual-branch architecture: it combines a frozen pre-trained vision encoder with a frozen, inference-only segmentation head to capture both high-level visual semantics and precise anatomical localization. These multimodal features are aligned via a lightweight pointwise convolution and fused to condition a Large Language Model (LLM), which is optimized using Low-Rank Adaptation (LoRA). We trained our model on a 16,000-sample subset of the PadChest dataset to generate reports directly in Spanish. Radixpert demonstrates comparable performance in clinical grounding and spatial reasoning, establishing a practical, resource-efficient path for developing specialized medical VLMs. Code is publicly available on [https://github.com/abdurafeyf/RadixpertV2](https://github.com/abdurafeyf/RadixpertV2)