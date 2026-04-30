---
# CSL-compatible fields
title: "ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation"
author:
  - literal: "Sergej Stanovcic"
  - literal: "Daniel Sliwowski"
  - literal: "Dongheui Lee"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26637"

# Custom fields
paper_id: "2604.26637"
paper_source: "arxiv"
domain: "robotics"
tags:
  []
architectures:
  []
datasets:
  - "REASSEMBLE"
concept_slugs:
  - "atlas-annotation-tool"
dataset_slugs:
  - "reassemble"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:13:11Z"
created_at: "2026-04-30T05:13:11Z"
---

# ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation

**Authors**: Sergej Stanovcic, Daniel Sliwowski, Dongheui Lee
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26637](https://arxiv.org/abs/2604.26637)

## Summary

ATLAS is a specialized annotation tool designed to address the challenges of labeling long-horizon robotic demonstrations by natively supporting synchronized multi-modal data, including multi-view video and proprioceptive signals. Featuring a modular dataset abstraction layer, the tool seamlessly integrates with standard formats like ROS bags and RLDS to streamline the annotation of complex manipulation tasks. Evaluations on contact-rich assembly datasets demonstrate that ATLAS significantly improves temporal precision and annotation efficiency compared to traditional vision-only tools.

## Key Contributions

- Introduces ATLAS, a modular, keyboard-centric annotation tool for long-horizon robotic action segmentation supporting multi-modal data synchronization.
- Demonstrates that time-synchronized proprioceptive signal visualization reduces per-action annotation time by 6% compared to ELAN.
- Shows that incorporating time-series data improves temporal boundary alignment by over 2.8% and reduces boundary error fivefold compared to vision-only approaches.

## Open Questions & Future Work

- [[cognitive-load-in-multimodal-annotation]]

## Key Concepts

- [[atlas-annotation-tool]]: A keyboard-centric, modular annotation tool for time-synchronized visualization of long-horizon robotic demonstrations.

## Archivist Review

The paper presents an annotation tool specifically addressing the multimodal data synchronization challenges in robotics. I approved the tool as a concept and the REASSEMBLE dataset, as both are distinct contributions to the robotics data pipeline. The open question regarding the cognitive load of multimodal annotation is a non-trivial research direction for human-in-the-loop robot learning systems.

### Approved Concepts
- ATLAS (Annotation Tool): It addresses the specific challenge of synchronizing multi-modal robotic data (vision and proprioceptive signals) for action boundary annotation, which is a significant bottleneck in robotics research.

### Approved Open Questions
- Optimizing Multimodal Annotation Efficiency: Addressing this tradeoff is critical for making large-scale manual annotation of robotic data scalable.

## Datasets

- [[reassemble]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26637)
- [PDF](https://arxiv.org/pdf/2604.26637)

