---
# CSL-compatible fields
title: "Inferring bifurcation diagrams of two distinct chaotic systems by a single machine"
author:
  - literal: "Jianmin Guo"
  - literal: "Yao Du"
  - literal: "Yizhen Yu"
  - literal: "Yong Zou"
  - literal: "Xingang Wang"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26632"

# Custom fields
paper_id: "2604.26632"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dual-channel-reservoir-computing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:13:25Z"
created_at: "2026-04-30T05:13:25Z"
---

# Inferring bifurcation diagrams of two distinct chaotic systems by a single machine

**Authors**: Jianmin Guo, Yao Du, Yizhen Yu, Yong Zou, Xingang Wang
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26632](https://arxiv.org/abs/2604.26632)

## Summary

This paper presents a dual-channel reservoir-computing scheme designed to learn the dynamics of two distinct chaotic systems using a single model. By incorporating a system-label channel and a parameter-control channel into a standard reservoir, the architecture can be trained on sparse time-series samples to perform both short-term prediction and long-term statistical characterization. The effectiveness of this approach is verified through the successful reconstruction of bifurcation diagrams for both Lorenz and Rössler systems, alongside successful applications to physical electronic circuits.

## Key Contributions

- Introduces a dual-channel reservoir-computing architecture that learns the dynamics of multiple chaotic systems within a single model.
- Demonstrates that the model reproduces long-term statistical properties and reconstructs full bifurcation diagrams from sparse, partial observations of two distinct systems.
- Validates the method on both numerical (Lorenz and Rössler) and experimental (Chua and Rössler circuits) chaotic benchmarks.

## Open Questions & Future Work

- [[scalability-of-multifunctional-reservoir-computing]]
- [[heterogeneous-dimension-mfrc-inference]]

## Key Concepts

- [[dual-channel-reservoir-computing]]: A reservoir computing architecture augmented with system-label and parameter-control channels to learn multiple dynamical systems simultaneously.

## Archivist Review

I approved the proposed dual-channel reservoir computing concept because it represents a distinct architectural approach for multiplexing dynamical learning, which is highly relevant for time-series modeling. I also approved the two open questions regarding scalability and heterogeneity, as they represent fundamental limitations in multifunctional learning architectures that will be recurring challenges in future research. All other items were evaluated against the standard of long-term utility and uniqueness.

### Approved Concepts
- Dual-channel reservoir-computing: It enables a single reservoir model to distinguish and learn the dynamics of multiple chaotic systems through system-label and parameter-control augmentation.

### Approved Open Questions
- Scalability of Multifunctional Reservoir Computing: Understanding the scalability limit of MFRC schemes is essential for their deployment in complex scenarios involving more than two chaotic systems.
- Multifunctional Inference of Heterogeneous Systems: Generalizing MFRC to heterogeneous systems of varying dimensionality would significantly expand its applicability.

## Links

- [Abstract](https://arxiv.org/abs/2604.26632)
- [PDF](https://arxiv.org/pdf/2604.26632)

