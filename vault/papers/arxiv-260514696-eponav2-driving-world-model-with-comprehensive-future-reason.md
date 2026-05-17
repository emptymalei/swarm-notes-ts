---
# CSL-compatible fields
title: "EponaV2: Driving World Model with Comprehensive Future Reasoning"
author:
  - literal: "Jiawei Xu"
  - literal: "Zhizhou Zhong"
  - literal: "Zhijian Shu"
  - literal: "Mingkai Jia"
  - literal: "Mingxiao Li"
  - literal: "Jia-Wang Bian"
  - literal: "Qian Zhang"
  - literal: "Kaicheng Zhang"
  - literal: "Jin Xie"
  - literal: "Jian Yang"
  - literal: "Wei Yin"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14696"

# Custom fields
paper_id: "2605.14696"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "autonomous-driving"
  - "world-models"
  - "trajectory-planning"
  - "representation-learning"
  - "flow-matching"
  - "future-forecasting"
architectures:
  []
datasets:
  - "navsim"
concept_slugs:
  - "flow-matching-group-relative-policy-optimization"
dataset_slugs:
  - "navsim"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:23:40Z"
created_at: "2026-05-17T05:23:40Z"
---

# EponaV2: Driving World Model with Comprehensive Future Reasoning

**Authors**: Jiawei Xu, Zhizhou Zhong, Zhijian Shu, Mingkai Jia, Mingxiao Li, Jia-Wang Bian, Qian Zhang, Kaicheng Zhang, Jin Xie, Jian Yang, Wei Yin
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14696](https://arxiv.org/abs/2605.14696)

## Summary

EponaV2 is a perception-free driving world model designed to overcome the limitations of standard next-frame prediction by forecasting comprehensive 3D geometric and semantic future representations. By decoding these future states, the model achieves a deeper understanding of the driving environment, which directly improves trajectory planning performance. Furthermore, the paper introduces a flow matching group relative policy optimization mechanism that applies LLM-inspired training techniques to enhance decision-making accuracy. EponaV2 achieves state-of-the-art results on NAVSIM benchmarks, outperforming existing perception-free driving models.

## Key Contributions

- Introduces EponaV2, a perception-free driving world model that enhances trajectory planning through comprehensive 3D geometry and semantic future forecasting.
- Develops a flow matching group relative policy optimization mechanism to refine trajectory planning, yielding state-of-the-art performance among perception-free models.
- Demonstrates significant performance gains on NAVSIM benchmarks, achieving +1.3 PDMS and +5.5 EPDMS improvements over current state-of-the-art perception-free approaches.

## Open Questions & Future Work

- [[mitigating-pseudo-label-imprecision-driving-models]]

## Key Concepts

- [[flow-matching-group-relative-policy-optimization]]: A policy optimization mechanism that uses flow matching and group-relative preference signals to refine trajectory planning in world models.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 1 open question(s), and 1 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Flow Matching Group Relative Policy Optimization: This represents a distinct synthesis of LLM training recipes and flow-matching-based world models for decision-making tasks, which is novel in the context of driving agents.

### Approved Open Questions
- Mitigating Pseudo-Label Imprecision: This is a critical scaling bottleneck, as the reliance on machine-generated labels to bypass expensive manual annotation often introduces persistent downstream performance limitations.

### Rejected Candidates
- [concept] Comprehensive Future Forecasting (`comprehensive-future-forecasting`) - not_novel: This is a descriptive goal rather than a novel, reusable algorithmic technique; it is a manifestation of standard multi-task prediction.

## Datasets

- [[navsim]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14696)
- [PDF](https://arxiv.org/pdf/2605.14696)

