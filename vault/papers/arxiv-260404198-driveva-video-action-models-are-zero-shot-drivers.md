---
# CSL-compatible fields
title: "DriveVA: Video Action Models are Zero-Shot Drivers"
author:
  - literal: "Mengmeng Liu"
  - literal: "Diankun Zhang"
  - literal: "Jiuming Liu"
  - literal: "Jianfeng Cui"
  - literal: "Hongwei Xie"
  - literal: "Guang Chen"
  - literal: "Hangjun Ye"
  - literal: "Michael Ying Yang"
  - literal: "Francesco Nex"
  - literal: "Hao Cheng"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04198"

# Custom fields
paper_id: "2604.04198"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "autonomous-driving"
  - "world-models"
  - "video-generation"
  - "zero-shot-learning"
  - "motion-planning"
architectures:
  []
datasets:
  - "nuscenes"
concept_slugs:
  []
dataset_slugs:
  - "nuscenes"
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:54:15Z"
created_at: "2026-04-07T04:54:15Z"
---

# DriveVA: Video Action Models are Zero-Shot Drivers

**Authors**: Mengmeng Liu, Diankun Zhang, Jiuming Liu, Jianfeng Cui, Hongwei Xie, Guang Chen, Hangjun Ye, Michael Ying Yang, Francesco Nex, Hao Cheng
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04198](https://arxiv.org/abs/2604.04198)

## Summary

DriveVA is an autonomous driving world model that addresses generalization challenges by jointly decoding future video and action sequences within a shared latent generative space. By utilizing a DiT-based decoder to align physical motion priors with scene evolution, the model achieves robust zero-shot performance and improved long-duration consistency. The approach shows significant reductions in collision rates and trajectory error across diverse driving benchmarks including NAVSIM, nuScenes, and CARLA.

## Key Contributions

- Proposes DriveVA, a world model that jointly decodes future visual forecasts and action sequences in a shared latent generative process to improve planning-scene consistency.
- Leverages pretrained large-scale video generation models to inherit priors on motion dynamics and physical plausibility for zero-shot driving.
- Achieves 90.9 PDM score on the NAVSIM benchmark and demonstrates significant performance gains in cross-domain generalization over state-of-the-art planners.

## Open Questions & Future Work

- [[causal-alignment-generative-driving-planning]]

## Archivist Review

The paper proposes an integration of video generation with action planning, but the core mechanics (joint decoding in a shared latent space) are often standard in modern generative architectures. I have focused on the fundamental challenge of causal alignment between generation and planning as the primary open question. NuScenes is approved as a foundational dataset, while other datasets were excluded as either simulators or emerging benchmarks.

### Approved Open Questions
- Causal Alignment in Driving Planning: This represents a fundamental challenge in unifying perception and control within generative architectures, impacting the reliability and safety of world-model-based autonomous driving.

### Rejected Candidates
- [open_question] Enhancing Visual Causal Reasoning (`improving-visual-causal-reasoning-for-driving-planning`) - other: The title and description are too broad; the rephrased version focuses more specifically on the architectural integration challenge identified in the paper.
- [dataset] NAVSIM (`NAVSIM`) - low_impact: The dataset is a very recent benchmark and its long-term viability as a standard reference is not yet established compared to more foundational datasets like nuScenes.
- [dataset] CARLA v2 (`CARLA-v2`) - not_reusable: CARLA is a widely used simulator environment rather than a static benchmark dataset; tracking specific versions is typically redundant for a vault focused on knowledge.

## Datasets

- [[nuscenes]]

## Links

- [Abstract](https://arxiv.org/abs/2604.04198)
- [PDF](https://arxiv.org/pdf/2604.04198)

