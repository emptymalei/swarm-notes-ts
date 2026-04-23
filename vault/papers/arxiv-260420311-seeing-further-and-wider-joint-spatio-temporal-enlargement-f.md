---
# CSL-compatible fields
title: "Seeing Further and Wider: Joint Spatio-Temporal Enlargement for Micro-Video Popularity Prediction"
author:
  - literal: "Dali Wang"
  - literal: "Yunyao Zhang"
  - literal: "Junqing Yu"
  - literal: "Yi-Ping Phoebe Chen"
  - literal: "Chen Xu"
  - literal: "Zikai Song"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20311"

# Custom fields
paper_id: "2604.20311"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "topology-aware-memory-bank"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:07:22Z"
created_at: "2026-04-23T05:07:22Z"
---

# Seeing Further and Wider: Joint Spatio-Temporal Enlargement for Micro-Video Popularity Prediction

**Authors**: Dali Wang, Yunyao Zhang, Junqing Yu, Yi-Ping Phoebe Chen, Chen Xu, Zikai Song
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20311](https://arxiv.org/abs/2604.20311)

## Summary

Micro-video popularity prediction (MVPP) is constrained by sparse temporal sampling and limited-capacity spatial retrieval memory. This paper proposes a joint spatio-temporal enlargement framework to address these bottlenecks. It utilizes a dual-pathway temporal module for enhanced long-sequence understanding and a topology-aware memory bank that uses hierarchical clustering to scale historical associations without unbounded storage. Experimental results on three MVPP benchmarks demonstrate significant performance gains over 11 strong baselines.

## Key Contributions

- Introduces a unified framework for micro-video popularity prediction that performs joint spatio-temporal enlargement for improved content understanding and historical retrieval.
- Develops a Temporal Enlargement module that adaptively fuses sparse and dense frame perception to overcome limitations of short-range sequence sampling.
- Introduces a Topology-Aware Memory Bank that enables infinite historical video association through hierarchical clustering and encoder-level updates, outperforming 11 baselines.

## Open Questions & Future Work

- [[scalability-of-topology-aware-memory-in-mvpp]]

## Key Concepts

- [[topology-aware-memory-bank]]: A memory architecture that clusters historical video content topologically and updates cluster encoders to achieve scalable long-term associations without linear storage growth.

## Archivist Review

The approval focuses on the Topology-Aware Memory Bank as a reusable pattern for scalable retrieval-augmented forecasting. Other proposed methods, such as the dual-pathway temporal module, were deemed too incremental to merit permanent architectural status. The open question was refined to emphasize the scaling limits of retrieval-based structures.

### Approved Concepts
- Topology-Aware Memory Bank: It solves the scalability bottleneck of flat retrieval memories in micro-video popularity prediction by using hierarchical clustering and feature updates instead of raw capacity expansion.

### Approved Open Questions
- Scalability of topology-aware memory: This is a fundamental bottleneck for deploying retrieval-augmented popularity prediction systems on large-scale social media platforms, where historical data is massive and non-stationary.

### Rejected Candidates
- [concept] Temporal Enlargement (`temporal-enlargement`) - not_novel: The dual-pathway approach of combining sparse and dense sampling is a relatively common heuristic in sequence modeling and does not constitute a sufficiently novel or standalone concept compared to the memory contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.20311)
- [PDF](https://arxiv.org/pdf/2604.20311)

