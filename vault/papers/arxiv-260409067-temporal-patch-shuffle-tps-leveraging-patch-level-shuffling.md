---
# CSL-compatible fields
title: "Temporal Patch Shuffle (TPS): Leveraging Patch-Level Shuffling to Boost Generalization and Robustness in Time Series Forecasting"
author:
  - literal: "Jafar Bakhshaliyev"
  - literal: "Johannes Burchert"
  - literal: "Niels Landwehr"
  - literal: "Lars Schmidt-Thieme"
  - literal: "Lars Schmidt-Thieme"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09067"

# Custom fields
paper_id: "2604.09067"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "data-augmentation"
  - "generalization"
  - "robustness"
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-patch-shuffle-tps"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:09:44Z"
created_at: "2026-04-13T05:09:44Z"
---

# Temporal Patch Shuffle (TPS): Leveraging Patch-Level Shuffling to Boost Generalization and Robustness in Time Series Forecasting

**Authors**: Jafar Bakhshaliyev, Johannes Burchert, Niels Landwehr, Lars Schmidt-Thieme, Lars Schmidt-Thieme
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09067](https://arxiv.org/abs/2604.09067)

## Summary

This paper introduces Temporal Patch Shuffle (TPS), a novel, model-agnostic data augmentation method designed to enhance generalization and robustness in time series forecasting. Unlike existing methods that may disrupt essential temporal coherence, TPS extracts overlapping patches and performs selective shuffling based on a variance-based heuristic before reconstructing the sequence. Extensive evaluation across multiple long-term and short-term forecasting benchmarks demonstrates that TPS consistently improves the performance of various prominent forecasting models.

## Key Contributions

- Introduced Temporal Patch Shuffle (TPS), a model-agnostic data augmentation technique that preserves local temporal coherence by selectively shuffling overlapping patches.
- Demonstrated consistent performance improvements across nine long-term forecasting datasets and four short-term datasets using various architectures including TSMixer, DLinear, PatchTST, TiDE, and LightTS.
- Provided empirical evidence that the variance-based ordering heuristic effectively balances increased sample diversity with the preservation of forecast-consistent local structures.

## Open Questions & Future Work

- [[unified-forecasting-augmentation-benchmarking]]

## Key Concepts

- [[temporal-patch-shuffle-tps]]: A model-agnostic data augmentation method for time series forecasting that increases sample diversity by shuffling overlapping temporal patches based on variance-based ordering while preserving local temporal structure.

## Archivist Review

I approved the Temporal Patch Shuffle (TPS) method as a distinct, reusable concept for time series augmentation that addresses the unique challenge of maintaining temporal coherence. I also approved a refined version of the unified benchmarking question, as this is a recurring bottleneck in the field of time series forecasting evaluation. The second proposed open question was rejected because it requested broader empirical testing rather than addressing a fundamental open research problem.

### Approved Concepts
- Temporal Patch Shuffle (TPS): TPS provides a model-agnostic, patch-level data augmentation strategy designed specifically to balance temporal coherence with sample diversity, a persistent challenge in time series forecasting.

### Approved Open Questions
- Unified Forecasting Augmentation Benchmarking: Without standardized benchmarks, assessing the generalizability and true impact of novel augmentation strategies like TPS remains problematic for the field.

### Rejected Candidates
- [open_question] Generalization to New Architectures (`augmentation-generalization-to-new-architectures`) - other: This is a request for further empirical validation rather than an exploration of a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.09067)
- [PDF](https://arxiv.org/pdf/2604.09067)

