---
# CSL-compatible fields
title: "EponaV2: Driving World Model with Comprehensive Future Reasoning"
author:
  - literal: "Jiawei Xu"
  - literal: "Zhizhou Zhong"
  - literal: "Zhijian Shu"
  - literal: "Mingkai Jia"
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
  - "semantic-segmentation"
  - "geometry-prediction"
  - "flow-matching"
architectures:
  []
datasets:
  - "NAVSIM"
concept_slugs:
  - "flow-matching-group-relative-policy-optimization"
dataset_slugs:
  - "navsim"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:01Z"
created_at: "2026-05-16T05:12:01Z"
---

# EponaV2: Driving World Model with Comprehensive Future Reasoning

**Authors**: Jiawei Xu, Zhizhou Zhong, Zhijian Shu, Mingkai Jia, Mingkai Jia, Mingxiao Li, Jia-Wang Bian, Qian Zhang, Kaicheng Zhang, Jin Xie, Jian Yang, Wei Yin
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14696](https://arxiv.org/abs/2605.14696)

## Summary

EponaV2 is a perception-free driving world model designed to overcome the limitations of simple next-frame image forecasting by predicting comprehensive future 3D and semantic representations. By incorporating these geometric and semantic modalities, the model achieves deeper scene understanding and improved trajectory planning. Additionally, it employs a novel flow matching group relative policy optimization mechanism, achieving state-of-the-art results on NAVSIM benchmarks.

## Key Contributions

- EponaV2 proposes a paradigm for perception-free driving world models that leverages comprehensive future representations including 3D geometry and semantic maps.
- Introduction of a flow matching group relative policy optimization mechanism that aligns planning with LLM-inspired training recipes.
- EponaV2 achieves SOTA performance among perception-free models on NAVSIM benchmarks, improving PDMS by +1.3 and EPDMS by +5.5.

## Open Questions & Future Work

- [[pseudo-label-imprecision-in-driving-world-models]]

## Key Concepts

- [[flow-matching-group-relative-policy-optimization]]: A policy optimization mechanism based on flow matching used to enhance trajectory planning accuracy in driving world models.

## Archivist Review

I have approved the core methodological contribution (flow matching group relative policy optimization) and the central dataset (NAVSIM). I also approved a well-articulated open question regarding the reliance on pseudo-labels in perception-free driving models, which is a significant bottleneck. I rejected the model name itself as it is paper-specific and not a reusable concept.

### Approved Concepts
- Flow matching group relative policy optimization: This mechanism provides a novel policy optimization approach for generative driving models, adapting LLM-style training to trajectory planning.

### Approved Open Questions
- Pseudo-label Imprecision in World Models: This identifies a foundational limitation for the scalability of perception-free autonomous driving, highlighting a bottleneck in existing self-supervised world model training.

### Rejected Candidates
- [concept] EponaV2 paradigm (`eponav2-paradigm`) - paper_local: This is a paper-specific model name rather than a distinct, reusable methodology.

## Datasets

- [[navsim]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14696)
- [PDF](https://arxiv.org/pdf/2605.14696)

