---
# CSL-compatible fields
title: "Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters"
author:
  - literal: "Hugo Cazaux"
  - literal: "Eyjólfur Ingi Ásgeirsson"
  - literal: "Hlynur Stefánsson"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06032"

# Custom fields
paper_id: "2605.06032"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "synthetic-data"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:15Z"
created_at: "2026-05-09T05:11:15Z"
---

# Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters

**Authors**: Hugo Cazaux, Eyjólfur Ingi Ásgeirsson, Hlynur Stefánsson
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06032](https://arxiv.org/abs/2605.06032)

## Summary

This paper investigates the role of synthetic data augmentation in deep time series forecasting through a massive, systematic empirical analysis. The study finds that the benefit of synthetic data is strongly contingent on the model architecture, favoring channel-mixing approaches over channel-independent ones. Furthermore, it reveals that effective use of synthetic data requires specific signal generators, such as Seasonal-Trend models, and careful training schedules to avoid significant performance degradation.

## Key Contributions

- Conducted a large-scale empirical study comprising 4,218 runs to evaluate the efficacy of synthetic time series data augmentation.
- Demonstrated that synthetic data utility is highly architecture-dependent: channel-mixing models often improve, while channel-independent models consistently underperform.
- Identified that only Seasonal-Trend-based synthetic signals consistently improve performance and provided actionable guidelines for augmentation strategies in low-resource settings.

## Open Questions & Future Work

- [[synthetic-data-scaling-laws-time-series]]
- [[architectural-gating-synthetic-data-receptiveness]]

## Archivist Review

I have approved the two open questions because they address fundamental unresolved bottlenecks regarding the scaling and architectural dependency of synthetic data in time series forecasting, which are identified as significant research gaps in the paper. I have not approved any concepts as the paper primarily presents an empirical evaluation of existing architectures and augmentation methods rather than introducing new, reusable algorithmic abstractions. The dataset candidates were not explicitly provided in the analysis input, so none were approved.

### Approved Open Questions
- Scaling laws for synthetic time series augmentation: Understanding scaling laws is critical for moving beyond empirical trial-and-error, enabling the design of more efficient training pipelines and predictable performance gains in data-scarce scenarios.
- Architectural gating of synthetic data receptiveness: Identifying the core architectural bottlenecks is essential for developing future forecasting architectures that are inherently robust to synthetic data mismatch and capable of leveraging diverse synthetic distributions.

## Links

- [Abstract](https://arxiv.org/abs/2605.06032)
- [PDF](https://arxiv.org/pdf/2605.06032)

