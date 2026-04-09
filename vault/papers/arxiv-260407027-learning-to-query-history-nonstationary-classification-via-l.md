---
# CSL-compatible fields
title: "Learning to Query History: Nonstationary Classification via Learned Retrieval"
author:
  - literal: "Jimmy Gammell"
  - literal: "Bishal Thapaliya"
  - literal: "Yoon Jung"
  - literal: "Riyasat Ohib, Bilel Fehri"
  - literal: "Deepayan Chakrabarti"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07027"

# Custom fields
paper_id: "2604.07027"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "nonstationarity"
  - "classification"
  - "retrieval-augmented-forecasting"
  - "distribution-shift"
architectures:
  []
datasets:
  []
concept_slugs:
  - "learned-discrete-retrieval-mechanism"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:54:39Z"
created_at: "2026-04-09T04:54:39Z"
---

# Learning to Query History: Nonstationary Classification via Learned Retrieval

**Authors**: Jimmy Gammell, Bishal Thapaliya, Yoon Jung, Riyasat Ohib, Bilel Fehri, Deepayan Chakrabarti
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07027](https://arxiv.org/abs/2604.07027)

## Summary

This paper addresses performance degradation in nonstationary classification by reframing the problem as a sequence-based prediction task conditioned on historical labeled data. The authors propose a learned discrete retrieval mechanism that uses input-dependent queries to select relevant historical examples, facilitating training on massive datasets stored on external filesystems. By utilizing a score-based gradient estimator, the retrieval mechanism and classifier are trained end-to-end, achieving superior robustness to distribution shifts while maintaining efficient VRAM utilization.

## Key Contributions

- Reframes nonstationary classification as a retrieval-augmented time series prediction problem to improve robustness against distribution shifts.
- Introduces a learned discrete retrieval mechanism that scales to large historical corpora by using input-dependent queries trained end-to-end.
- Demonstrates improved robustness on the Amazon Reviews '23 dataset and synthetic benchmarks while ensuring VRAM usage remains independent of the total corpus size.

## Open Questions & Future Work

- [[improving-retrieval-training-stability]]
- [[dynamic-key-updates-for-retrieval]]

## Key Concepts

- [[learned-discrete-retrieval-mechanism]]: A retrieval mechanism that uses input-dependent queries and score-based gradient estimation to sample relevant historical labeled examples for nonstationary classification.

## Archivist Review

I approved the retrieval mechanism concept as it provides a modular, reusable approach to managing historical context in nonstationary settings. I also approved two open questions concerning training stability and dynamic index updating, as these represent fundamental challenges in making retrieval-augmented systems robust over time. Routine dataset candidates were rejected to prioritize core algorithmic developments.

### Approved Concepts
- Learned Discrete Retrieval Mechanism: It enables training with large-scale historical data while maintaining constant VRAM, solving the bottleneck of scaling nonstationary classification to long historical sequences.

### Approved Open Questions
- Improving Retrieval Training Stability: Training stability is a critical bottleneck for deploying retrieval-augmented systems in real-world nonstationary environments, where high gradient variance can lead to sub-optimal convergence.
- Dynamic Key Updates for Retrieval: Static keys fail to adapt to nonstationary environments where the relevance criteria for historical data may shift over time, limiting the long-term effectiveness of the retrieval mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.07027)
- [PDF](https://arxiv.org/pdf/2604.07027)

