---
layout: page
title: Decoding Neural Activity Information Based on Brain Imaging
description: CAS Strategic Priority Research Program - Dual-stream cross-modal decoding architecture for EEG-based visual perception
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

**Project Type:** Strategic Priority Research Program of the Chinese Academy of Sciences (Category B)  
**Duration:** Sep 2023 – Present  
**Role:** Core Member | Lead for Topic 2: "Decoding Methods for Visual Perception based on Brain Imaging"  
**Institution:** Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences

## Overview

This project focuses on developing advanced decoding methods for neural activity information using brain imaging techniques, specifically targeting visual perception tasks. As a core member leading Topic 2, I designed and implemented a sophisticated dual-stream cross-modal decoding architecture to address the high-dimensional spatiotemporal characteristics of EEG signals.

## Key Technical Contributions

### Architecture Design

Designed and built a **dual-stream cross-modal decoding architecture** to effectively process the complex spatiotemporal patterns inherent in EEG signals. This architecture enables simultaneous processing of brain signals and visual stimuli, facilitating robust cross-modal alignment.

### Feature Extraction

- **Visual Features:** Utilized **Deep Residual Networks (ResNet)** to extract high-level semantic features from visual images
- **Temporal Patterns:** Combined ResNet features with **Multi-Head Self-Attention mechanisms** to capture millisecond-level dynamic temporal patterns in brain signals
- This approach enables the model to understand both spatial visual semantics and temporal neural dynamics

### Alignment & Generalization

- Achieved **high-precision semantic alignment** between brain and visual features in latent space via **contrastive learning**
- Addressed multi-subject variability by applying machine learning algorithms based on **multi-source domain generalization** (metric learning)
- This ensures the model's robustness across different subjects and experimental conditions

### Hardware Integration

The project integrates signal processing, pattern recognition, and AI algorithms, with the ultimate goal of deployment on **FPGA hardware platforms** for real-time neural decoding applications.

## Impact

This research contributes to advancing the field of brain-computer interfaces by providing a robust framework for decoding visual perception from brain imaging data, with potential applications in assistive technologies and neural prosthetics.
