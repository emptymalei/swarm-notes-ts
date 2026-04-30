---
# CSL-compatible fields
title: "STLGT: A Scalable Trace-Based Linear Graph Transformer for Tail Latency Prediction in Microservices"
author:
  - literal: "Yongliang Ding"
  - literal: "Qigong Bi"
  - literal: "Peng Pu"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26422"

# Custom fields
paper_id: "2604.26422"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "deathstarbench"
concept_slugs:
  []
dataset_slugs:
  - "deathstarbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:14:00Z"
created_at: "2026-04-30T05:14:00Z"
---

# STLGT: A Scalable Trace-Based Linear Graph Transformer for Tail Latency Prediction in Microservices

**Authors**: Yongliang Ding, Qigong Bi, Peng Pu
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26422](https://arxiv.org/abs/2604.26422)

## Summary

STLGT is a scalable forecasting framework designed for end-to-end tail-latency prediction in microservice architectures. By representing request traces as span graphs, the model uses a structure-aware linear Transformer to efficiently propagate dependency information while employing a decoupled module to handle non-stationary workload dynamics. Evaluation across multiple microservice datasets shows that STLGT outperforms existing GNN-based baselines in both forecasting accuracy and computational efficiency.

## Key Contributions

- Introduces STLGT, a per-API predictor using a structure-aware linear graph Transformer to encode service traces as span graphs for tail-latency forecasting.
- Achieves linear inference complexity relative to span graph size, enabling 12x faster CPU inference compared to PERT-GNN.
- Demonstrates an 8.5% improvement in MAPE over existing baselines on microservice latency forecasting benchmarks under bursty traffic conditions.

## Open Questions & Future Work

- [[adapting-to-microservice-topology-drift]]

## Archivist Review

The paper proposes a specific architecture (STLGT) for microservice latency forecasting, which is rejected as a paper-local contribution. I approved the microservice topology drift open question as it identifies a substantial and widely applicable bottleneck in deploying predictive models within dynamic service architectures. DeathStarBench is approved as a standard and named benchmark dataset for microservice evaluation.

### Approved Open Questions
- Adapting to Microservice Topology Drift: Proactive auto-scaling systems require high model reliability; drift in the underlying service topology renders static predictors inaccurate, necessitating automated, efficient adaptation mechanisms to maintain SLO compliance in dynamic environments.

### Rejected Candidates
- [concept] STLGT (Scalable Trace-based Linear Graph Transformer) (`stlgt`) - paper_local: This is a paper-specific architecture/framework name rather than a reusable core mechanism.
- [concept] Span Graph Encoding (`span-graph-encoding`) - not_reusable: This is a representation specific to microservice trace modeling and lacks the broader applicability required for a vault entry.

## Datasets

- [[deathstarbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26422)
- [PDF](https://arxiv.org/pdf/2604.26422)

