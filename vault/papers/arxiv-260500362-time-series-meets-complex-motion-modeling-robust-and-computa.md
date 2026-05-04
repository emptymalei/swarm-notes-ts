---
# CSL-compatible fields
title: "Time-series Meets Complex Motion Modeling: Robust and Computational-effective Motion Predictor for Multi-object Tracking"
author:
  - literal: "Nhat-Tan Do"
  - literal: "Le-Huy Tu"
  - literal: "Nhi Ngoc-Yen Nguyen"
  - literal: "Dieu-Phuong Nguyen"
  - literal: "Trong-Hop Do"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00362"

# Custom fields
paper_id: "2605.00362"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-convolutional-motion-predictor-tcmp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:16:10Z"
created_at: "2026-05-04T05:16:10Z"
---

# Time-series Meets Complex Motion Modeling: Robust and Computational-effective Motion Predictor for Multi-object Tracking

**Authors**: Nhat-Tan Do, Le-Huy Tu, Nhi Ngoc-Yen Nguyen, Dieu-Phuong Nguyen, Trong-Hop Do
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00362](https://arxiv.org/abs/2605.00362)

## Summary

This paper introduces the Temporal Convolutional Motion Predictor (TCMP), a highly efficient framework designed to address the challenges of complex, non-linear object motion in multi-object tracking (MOT). By utilizing a modified Temporal Convolutional Network (TCN) with dilated convolutions, the method effectively predicts object trajectories across varying temporal contexts. Experimental results demonstrate that TCMP achieves state-of-the-art tracking performance while significantly outperforming previous complex generative models in both parameter count and computational complexity.

## Key Contributions

- Introduces TCMP, a framework for MOT based on a modified TCN with dilated convolutions and a regression head, designed for efficient non-linear motion modeling.
- TCMP achieves state-of-the-art performance on key MOT metrics, including HOTA (63.4%), IDF1 (65.0%), and AssA (49.1%).
- Demonstrates substantial computational efficiency, reducing parameter count to 1.4% and FLOPs to 5% of the previous SOTA method.

## Open Questions & Future Work

- [[balancing-context-length-and-efficiency-in-mot-motion-prediction]]

## Key Concepts

- [[temporal-convolutional-motion-predictor-tcmp]]: A motion prediction framework for multi-object tracking that employs a modified TCN with dilated convolutions and a regression head for efficient trajectory modeling.

## Archivist Review

I have approved the TCMP framework as it provides a clear, reusable architectural alternative to computationally expensive generative models in motion prediction. The open question was approved for its focus on the fundamental trade-off between temporal context, complexity, and real-time performance in tracking, which extends beyond this specific paper. No datasets were approved as none were uniquely identified as a novel, central contribution.

### Approved Concepts
- Temporal Convolutional Motion Predictor (TCMP): It represents an efficient, purpose-built architectural alternative to complex generative models for non-linear motion prediction.

### Approved Open Questions
- Context Length vs Efficiency in MOT: Managing long-range temporal dependencies without prohibitive computational costs is a fundamental bottleneck for real-time motion prediction in complex environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.00362)
- [PDF](https://arxiv.org/pdf/2605.00362)

