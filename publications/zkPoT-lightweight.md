---
title: >-
  Towards Practical Zero-Knowledge Proofs of Training for Simple Models
slug: zkPoT-lightweight
description: Zero-Knowledge Proofs
tags:
  - neural networks
  - circom
  - zero-knowledge
  - integrity
added: 2025-12-24T19:00:00.000Z
---

[See paper here](https://assets.tina.io/1fb09d03-9237-4c49-aaa9-d024a83c7ac7/zkPoT-lightweight.pdf)

# Abstract

As machine learning models are increasingly deployed in critical decision-making systems, verifying the integrity of the training process without compromising data privacy has become a significant challenge. While recent frameworks for Zero-Knowledge Proofs of Training (zkPoT), such as those by Garg et al., demonstrate feasibility, they often rely on heavy cryptographic machinery that creates barriers to practical implementation and understanding. This project bridges that gap by presenting a lightweight, reproducible prototype for verifiable training using the Circom language and the Groth16 proving system. We move beyond simple single-step verifications to implement Mini-Batch Gradient Descent, demonstrating how data-parallelism can be achieved in a zero-knowledge circuit. Additionally, we extend this work to a Multi-Layer Perceptron (MLP) with ReLU activation, proving the correctness of inference and weight updates on secret data. We address the technical challenges of implementing fixed-point arithmetic and stateful loops within Rank-1 Constraint Systems (R1CS). Finally, we provide an experimental evaluation of scalability, benchmarking the relationship between batch size, circuit constraints, and proof generation time, confirming that verifiable training is tractable for small-scale batches on consumer hardware.