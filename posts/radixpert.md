---
title: >-
  Radixpert: A Staged Adaptation and Hierarchical Fusion Framework for Radiology
  VLMs
slug: radixpert
description: Radiology Report Generation (2D)
tags:
  - technical
  - learning
  - work
added: 2025-05-29T19:00:00.000Z
---

# Abstract

Automated radiology report generation has emerged as a critical application for improving clinical efficiency and reducing physician workload. This paper presents Radixpert, a novel vision-language model that leverages multi-dataset training and hierarchical cross-modal fusion for enhanced radiology report generation. Our approach utilizes the Llama 3.2-11B-Vision-Instruct model as the foundation, enhanced with a Multi Stage Adaptive LoRA (MSA-LoRA) fine-tuning methodology and a Hierarchical Cross-Modal Fusion (HCF) architecture. We trained our model on a combination of ROCO v2 (15,000 samples) and PadChest (16,000 samples) datasets, achieving state-of-the- art performance across multiple evaluation metrics. Radixpert demonstrates superior clinical accuracy with a BLEU-4 score of 0.194, CIDEr of 0.478, and RadCliQ-v1 of 0.823, outperforming existing methods. Code and model weights will be made available upon publication to support reproducible research in medical AI.

[Paper](../public/Radixpert__A_Staged_Adaptation_and_Hierarchical_Fusion_Framework_for_Radiology_VLMs.pdf)
