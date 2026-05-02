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
processed_at: "2026-05-02T05:12:01Z"
created_at: "2026-05-02T05:12:01Z"
---

# ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation

**Authors**: Sergej Stanovcic, Daniel Sliwowski, Dongheui Lee
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26637](https://arxiv.org/abs/2604.26637)

## Summary

ATLAS is a specialized annotation tool designed to address the challenges of labeling long-horizon robotic demonstrations by integrating multi-view video with time-synchronized proprioceptive signals. Unlike traditional vision-only tools, it supports native import of robotics-standard formats like ROS bags and RLDS, facilitating efficient segmentation of complex tasks. The tool features a modular architecture for extensibility and a keyboard-centric interface, resulting in significant improvements in both annotation speed and temporal boundary precision for contact-rich assembly tasks.

## Key Contributions

- Introduced ATLAS, a modular, multi-modal annotation tool designed for long-horizon robotic action segmentation.
- Enabled native integration and synchronized visualization of multi-view video and proprioceptive robotic signals (ROS bags, RLDS).
- Demonstrated 6% faster annotation and a fivefold reduction in boundary error on contact-rich assembly tasks compared to vision-only approaches.

## Open Questions & Future Work

- [[cognitive-load-in-multimodal-annotation]]

## Key Concepts

- [[atlas-annotation-tool]]: A modular annotation tool for long-horizon robotic demonstrations that enables time-synchronized visualization of multi-view video and proprioceptive time-series signals.

## Archivist Review

I have approved the ATLAS annotation tool and the associated REASSEMBLE dataset, as they represent a notable contribution to the robotics data pipeline. I also approved the open question regarding the cognitive load of multi-modal annotation, as it identifies a substantive research bottleneck in high-quality data generation for robot learning. The selection was made to capture these specific, reusable tools and research questions rather than transient experimental results.

### Approved Concepts
- ATLAS (Annotation Tool): Addresses the specific bottleneck of multi-modal, long-horizon annotation in robotics which currently lacks integrated tools.

### Approved Open Questions
- Cognitive Load in Multimodal Annotation: Human-in-the-loop annotation is a primary bottleneck for scaling robot learning; understanding these cognitive trade-offs is essential for sustainable data creation.

## Datasets

- [[reassemble]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26637)
- [PDF](https://arxiv.org/pdf/2604.26637)

