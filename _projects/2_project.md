---
layout: page
title: Neuroscience-Inspired Tri-Modality Alignment Framework
description: Multi-Modal Non-Invasive BCI - Brain-Vision-Language alignment with LLM integration
img: assets/img/3.jpg
importance: 1
category: work
giscus_comments: true
---

**Project Type:** Guangdong Provincial Key Laboratory Project  
**Duration:** Jan 2024 – Present  
**Role:** Core R&D Member  
**Research Topic:** A Neuroscience-Inspired Framework for Tri-Modality Alignment of Brain Signals, Vision, and Language

## Overview

This project breaks the limitations of traditional binary (brain-vision) alignment by constructing a joint embedding space for **Brain-Vision-Language** tri-modality alignment. The framework is inspired by neuroscience principles, particularly the dual-stream processing mechanism of the human visual system.

## Key Innovations

### Tri-Modality Alignment
Constructed a **joint embedding space** that simultaneously aligns brain signals, visual images, and language descriptions. This approach enables richer semantic understanding compared to traditional binary alignment methods.

### LLM Integration
- Innovatively introduced **Large Language Models (LLMs)** to generate fine-grained text descriptions as "semantic anchors"
- Utilized **BLIP-2** to generate dynamic text descriptions for visual stimuli
- Enforced high-precision alignment through **cross-modal contrastive learning**

### Neuroscience Inspiration
- Simulated the **dual-stream processing mechanism** of the human visual system
- Used **center-surround antagonism** and **fast saliency detection** (mimicking the V1 cortex) to extract edge, brightness, and color features
- This biologically-inspired approach addresses the "feature-physiological mismatch" problem in neural decoding

### Dynamic Semantic Guidance
Designed a **Dynamic Loss Adjustment** optimization strategy to adaptively balance the weights of low-level features and high-level semantics during training, simulating the brain's dynamic "perception-to-cognition" process.

## Research Achievements

### Publication
**First Author** of the paper: *"A Neuroscience-Inspired Framework for Tri-Modality Alignment of Brain Signals, Vision, and Language"*  
**Status:** Under Review at **ICLR 2026**

### Performance
Achieved **State-of-the-Art (SOTA)** performance in 200-class Zero-shot image retrieval tasks on large-scale datasets:
- **THINGS-EEG2**
- **THINGS-MEG**

## Impact

This framework represents the first attempt to incorporate language as a semantic bridge in brain-vision alignment, opening new directions for multi-modal neural decoding research.
