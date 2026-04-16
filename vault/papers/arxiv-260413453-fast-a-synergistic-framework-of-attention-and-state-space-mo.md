---
# CSL-compatible fields
title: "FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction"
author:
  - literal: "Xinjin Li"
  - literal: "Jinghan Cao"
  - literal: "Mengyue Wang"
  - literal: "Yue Wu"
  - literal: "Longxiang Yan"
  - literal: "Yeyang Zhou"
  - literal: "Ziqi Sha"
  - literal: "Yu Ma"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13453"

# Custom fields
paper_id: "2604.13453"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "traffic-prediction"
  - "spatiotemporal-modeling"
  - "attention"
  - "state-space-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-spatial-temporal-architecture"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:57Z"
created_at: "2026-04-16T05:06:57Z"
---

# FAST: A Synergistic Framework of Attention and State-space Models for Spatiotemporal Traffic Prediction

**Authors**: Xinjin Li, Jinghan Cao, Mengyue Wang, Yue Wu, Longxiang Yan, Yeyang Zhou, Ziqi Sha, Yu Ma
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13453](https://arxiv.org/abs/2604.13453)

## Summary

FAST is a spatiotemporal traffic forecasting framework that addresses the efficiency-expressiveness trade-off by combining temporal attention modules with a Mamba-based spatial module. The model employs a Temporal-Spatial-Temporal architecture that captures global dependencies with linear complexity, outperforming existing Transformer, GNN, and Mamba-based models. Empirical results on three major traffic benchmarks demonstrate that FAST achieves superior accuracy and scalability by integrating multi-source spatiotemporal embeddings and hierarchical skip prediction.

## Key Contributions

- Introduces FAST, a unified Temporal-Spatial-Temporal framework that leverages both attention and selective state-space models for efficient traffic forecasting.
- Integrates a Mamba-based spatial module to achieve linear complexity in modeling long-range inter-sensor dependencies, addressing the limitations of quadratic Transformer-based approaches.
- Achieves state-of-the-art performance on PeMS04, PeMS07, and PeMS08 benchmarks, providing up to 4.3% lower RMSE and 2.8% lower MAE compared to competitive baselines.

## Open Questions & Future Work

- [[adaptive-spatial-structure-modeling]]

## Key Concepts

- [[temporal-spatial-temporal-architecture]]: A sandwich-style architecture that alternates temporal attention and Mamba-based spatial modules to process graph-structured sequence data with linear complexity.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Temporal-Spatial-Temporal Architecture: This architecture formalizes the strategy of sandwiching state-space models between attention-based temporal stages to balance expressivity and complexity in spatiotemporal tasks.

### Approved Open Questions
- Adaptive Spatial Structure Modeling: Moving beyond fixed graphs is essential for creating robust, generalizable spatiotemporal models in real-world environments where connectivity patterns evolve over time.

### Rejected Candidates
- [open_question] Expanding Spatiotemporal Forecasting Capabilities (`expanding-spatiotemporal-forecasting-capabilities`) - other: The candidate was overly broad and included boilerplate requests for more data/scenarios; I replaced it with a more specific, technically focused question about adaptive spatial modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.13453)
- [PDF](https://arxiv.org/pdf/2604.13453)

