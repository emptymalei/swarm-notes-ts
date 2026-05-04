---
# CSL-compatible fields
title: "GaMMA: Towards Joint Global-Temporal Music Understanding in Large Multimodal Models"
author:
  - literal: "Zuyao You"
  - literal: "Zhesong Yu"
  - literal: "Mingyu Liu"
  - literal: "Bilei Zhu"
  - literal: "Yuan Wan"
  - literal: "Zuxuan Wu"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00371"

# Custom fields
paper_id: "2605.00371"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "MusicBench"
concept_slugs:
  []
dataset_slugs:
  - "musicbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:16:03Z"
created_at: "2026-05-04T05:16:03Z"
---

# GaMMA: Towards Joint Global-Temporal Music Understanding in Large Multimodal Models

**Authors**: Zuyao You, Zhesong Yu, Mingyu Liu, Bilei Zhu, Yuan Wan, Zuxuan Wu
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00371](https://arxiv.org/abs/2605.00371)

## Summary

GaMMA is a large multimodal model that leverages a mixture-of-experts audio encoder to unify temporal and non-temporal music understanding tasks. Building on an LLaVA-style architecture, the model undergoes a progressive training pipeline involving pretraining, supervised fine-tuning, and reinforcement learning. To validate its performance, the authors introduce MusicBench, a large-scale human-curated evaluation suite that sets a new standard for benchmarking musical content understanding in LMMs.

## Key Contributions

- Introduces GaMMA, an LMM incorporating a mixture-of-experts audio encoder architecture to unify global and temporal music understanding.
- Proposes a progressive training pipeline integrating pretraining, supervised fine-tuning, and reinforcement learning for enhanced musical content comprehension.
- Introduces MusicBench, a comprehensive benchmark containing 3,739 human-curated questions, establishing new performance standards with 79.3% accuracy on temporal and 81.3% on global subtasks.

## Archivist Review

The proposed MusicBench was approved as a dataset, as it serves as a standardized evaluation benchmark for multimodal music understanding. No new methodological concepts were identified that meet the high bar for permanent vault inclusion, as the model architecture is a standard LLaVA-style adaptation of MoE and progressive training. No novel, technically challenging open research questions were explicitly formulated beyond general scaling goals.

### Rejected Candidates
- [concept] MusicBench (`musicbench`) - other: This candidate is categorized as a benchmark dataset, not a methodological concept; it is approved as a dataset instead.

## Datasets

- [[musicbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.00371)
- [PDF](https://arxiv.org/pdf/2605.00371)

