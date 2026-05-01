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
domain: "computer-vision"
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
processed_at: "2026-05-01T05:24:58Z"
created_at: "2026-05-01T05:24:58Z"
---

# ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation

**Authors**: Sergej Stanovcic, Daniel Sliwowski, Dongheui Lee
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26637](https://arxiv.org/abs/2604.26637)

## Summary

ATLAS is a specialized annotation tool designed to streamline the labeling of long-horizon robotic demonstrations by integrating multi-view video with synchronized proprioceptive time-series data. The tool features a modular architecture that natively supports standard robotics formats like ROS bags and RLDS, facilitating easier integration into diverse research pipelines. By leveraging a keyboard-centric interface and multi-modal visualization, ATLAS significantly reduces annotation effort while substantially improving temporal boundary precision in complex, contact-rich assembly tasks.

## Key Contributions

- Introduces ATLAS, a modular, keyboard-centric tool for synchronizing and annotating multi-modal robotic data.
- Reduces average per-action annotation time by at least 6% compared to existing ELAN tools.
- Improves temporal alignment by 2.8% and reduces boundary error fivefold by incorporating time-series signals over vision-only approaches.

## Open Questions & Future Work

- [[cognitive-load-in-multimodal-annotation]]

## Key Concepts

- [[atlas-annotation-tool]]: A modular, keyboard-centric annotation tool designed for long-horizon robotic action segmentation using synchronized multi-modal data.

## Archivist Review

I have approved the ATLAS annotation tool and the associated open question regarding the cognitive load of multimodal annotation. These entries address critical bottlenecks in human-in-the-loop data labeling for long-horizon robotic tasks. The REASSEMBLE dataset is also approved as a key reference for robotic assembly benchmarks.

### Approved Concepts
- ATLAS (Annotation Tool): Provides a specialized, modular solution for annotating multi-modal robotic data (video + proprioception) which addresses current bottlenecks in robotics research.

### Approved Open Questions
- Multimodal Annotation Cognitive Load: Understanding the trade-off between annotation speed and accuracy is critical for developing scalable data pipelines for robotic learning, where human-provided ground truth is a significant bottleneck.

## Datasets

- [[reassemble]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26637)
- [PDF](https://arxiv.org/pdf/2604.26637)

