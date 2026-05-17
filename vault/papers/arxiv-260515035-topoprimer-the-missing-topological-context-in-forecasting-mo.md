---
# CSL-compatible fields
title: "TopoPrimer: The Missing Topological Context in Forecasting Models"
author:
  - literal: "Zara Zetlin"
  - literal: "Kayhan Moharreri"
  - literal: "Maria Safi"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15035"

# Custom fields
paper_id: "2605.15035"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "topoprimer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:22:46Z"
created_at: "2026-05-17T05:22:46Z"
---

# TopoPrimer: The Missing Topological Context in Forecasting Models

**Authors**: Zara Zetlin, Kayhan Moharreri, Maria Safi
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15035](https://arxiv.org/abs/2605.15035)

## Summary

TopoPrimer is a novel forecasting framework that integrates the global topological structure of time-series populations—computed via persistent homology and spectral sheaf coordinates—as explicit contextual input. It acts as either a token-level feature or a lightweight adapter for pre-trained backbones, proving effective across both zero-shot and fine-tuned settings. Evaluations on major benchmarks like ECL demonstrate significant gains in predictive accuracy, particularly in challenging regimes such as seasonal demand spikes and cold-start scenarios.

## Key Contributions

- Introduces TopoPrimer, a framework that incorporates global topological structure via persistent homology and spectral sheaf coordinates to enhance forecasting models.
- Achieves up to 7.3% improvement in MSE on the ECL benchmark when applied to Chronos and TimesFM models.
- Demonstrates superior robustness during seasonal demand spikes, maintaining accuracy within 10% compared to 50% degradation in baseline models.
- Reduces cold-start MAE by 27% by leveraging population-level topological context.

## Open Questions & Future Work

- [[multi-parameter-persistent-homology-forecasting]]

## Key Concepts

- [[topoprimer]]: A forecasting framework that injects global topological structure of time-series populations via persistent homology and spectral sheaf coordinates as explicit model input.

## Archivist Review

I approved TopoPrimer as a novel, modular architectural adaptation for injecting topological context into forecasting models. The open question regarding multi-parameter persistent homology captures a concrete, non-trivial research direction in temporal topological data analysis. Other candidates were rejected to prioritize the most impactful contributions in accordance with the scarcity policy.

### Approved Concepts
- TopoPrimer: Provides a novel, model-agnostic method to inject global population-level topology into forecasting backbones, addressing gaps in cold-start and seasonal performance.

### Approved Open Questions
- Multi-Parameter Topological Forecasting Extensions: Identifying better ways to capture higher-order topological relational dynamics is crucial for improving forecasting robustness in complex, non-stationary data regimes.

## Links

- [Abstract](https://arxiv.org/abs/2605.15035)
- [PDF](https://arxiv.org/pdf/2605.15035)

