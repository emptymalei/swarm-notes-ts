---
# CSL-compatible fields
title: "EagleVision: A Multi-Task Benchmark for Cross-Domain Perception in High-Speed Autonomous Racing"
author:
  - literal: "Zakhar Yagudin"
  - literal: "Murad Mebrahtu"
  - literal: "Ren Jin"
  - literal: "Jiaqi Huang"
  - literal: "Yujia Yue"
  - literal: "Dzmitry Tsetserukou"
  - literal: "Jorge Dias"
  - literal: "Majid Khonji"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11400"

# Custom fields
paper_id: "2604.11400"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "autonomous-racing"
  - "3d-detection"
  - "trajectory-prediction"
  - "domain-generalization"
  - "lidar-perception"
architectures:
  []
datasets:
  - "eaglevision-benchmark-dataset"
concept_slugs:
  []
dataset_slugs:
  - "eaglevision-benchmark-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:03:17Z"
created_at: "2026-04-14T05:03:17Z"
---

# EagleVision: A Multi-Task Benchmark for Cross-Domain Perception in High-Speed Autonomous Racing

**Authors**: Zakhar Yagudin, Murad Mebrahtu, Ren Jin, Jiaqi Huang, Yujia Yue, Dzmitry Tsetserukou, Jorge Dias, Majid Khonji
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11400](https://arxiv.org/abs/2604.11400)

## Summary

EagleVision is a multi-task benchmark designed to address the unique perception challenges posed by high-speed autonomous racing, such as extreme velocities and significant domain shifts. It provides a standardized evaluation protocol for 3D detection and trajectory prediction using a combined dataset of over 16,000 annotated frames from real racing competitions and simulation. The authors employ a dataset-centric transfer framework to evaluate cross-domain generalization, revealing that intermediate pretraining with real-world racing data significantly improves performance over urban-only or simulator-only baselines.

## Key Contributions

- Introduces EagleVision, a unified LiDAR-based multi-task benchmark for 3D detection and trajectory prediction specifically designed for high-speed autonomous racing dynamics.
- Provides 16,056 frames of annotated data across Indy Autonomous Challenge, A2RL Real competition, and simulator-generated environments to bridge the domain gap in high-speed perception.
- Demonstrates through a dataset-centric transfer framework that intermediate pretraining on real racing data provides superior domain adaptation compared to simulator-only approaches, achieving an NDS of 0.726 on the A2RL benchmark.

## Open Questions & Future Work

- [[racing-domain-generalization-bottleneck]]

## Archivist Review

The EagleVision benchmark is a significant multi-task dataset for high-speed racing perception, which qualifies for a dataset entry. I have consolidated the open question regarding racing-specific domain generalization into a more focused, high-level research direction, as the original submission contained too much boilerplate. No new concepts were approved as the paper focuses on benchmark development rather than a novel, reusable algorithmic mechanism.

### Approved Open Questions
- Autonomous Racing Domain Generalization: Bridging the sim-to-real gap is the primary bottleneck for deploying autonomous agents in high-velocity, high-uncertainty scenarios where safety and reaction time are critical.

### Rejected Candidates
- [open_question] Generalization in Autonomous Racing (`domain-adaptation-high-speed-racing`) - duplicate_existing: The candidate was rewritten to be more concise and aligned with the vault's style for open question definitions.

## Datasets

- [[eaglevision-benchmark-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11400)
- [PDF](https://arxiv.org/pdf/2604.11400)

