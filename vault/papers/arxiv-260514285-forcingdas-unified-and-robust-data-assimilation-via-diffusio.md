---
# CSL-compatible fields
title: "ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing"
author:
  - literal: "Yixuan Jia"
  - literal: "Siyi Chen"
  - literal: "Yida Pan"
  - literal: "Xiao Li"
  - literal: "Lianghe Shi"
  - literal: "Chanyong Jung"
  - literal: "Haijie Yuan"
  - literal: "Ismail Alkhouri"
  - literal: "Yue Cynthia Wu"
  - literal: "Saiprasad Ravishankar"
  - literal: "Jeffrey A Fessler"
  - literal: "Qing Qu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14285"

# Custom fields
paper_id: "2605.14285"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting horizon"
  - "seasonality handling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "forcingdas"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:25:19Z"
created_at: "2026-05-17T05:25:19Z"
---

# ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing

**Authors**: Yixuan Jia, Siyi Chen, Yida Pan, Xiao Li, Lianghe Shi, Chanyong Jung, Haijie Yuan, Ismail Alkhouri, Yue Cynthia Wu, Saiprasad Ravishankar, Jeffrey A Fessler, Qing Qu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14285](https://arxiv.org/abs/2605.14285)

## Summary

ForcingDAS addresses the fragility of traditional frame-to-frame data assimilation models by leveraging diffusion forcing to learn a joint-trajectory prior. This approach effectively captures long-horizon temporal dependencies and mitigates error accumulation in non-Markovian systems. Crucially, the framework allows a single trained model to span the entire spectrum from filtering to smoothing via adaptive inference scheduling, eliminating the need for retraining across different regimes. Experimental results demonstrate robust performance improvements over specialized baselines in complex dynamical scenarios including atmospheric state estimation.

## Key Contributions

- Introduces ForcingDAS, a data assimilation framework that learns a joint-trajectory prior to mitigate error accumulation in non-Markovian dynamical systems.
- Enables a unified inference pipeline where a single model performs nowcasting, fixed-lag smoothing, and batch reanalysis by adjusting the inference schedule.
- Outperforms specialized learned and classical baselines across 2D Navier-Stokes, precipitation, and global atmospheric state estimation benchmarks.

## Open Questions & Future Work

- [[unified-data-assimilation-regimes]]
- [[causal-smoothing-limitations]]

## Key Concepts

- [[forcingdas]]: A unified data assimilation framework that utilizes diffusion forcing to learn a joint-trajectory prior, enabling robust performance across filtering and smoothing tasks without retraining.

## Archivist Review

I approved the core framework 'ForcingDAS' and two foundational open questions regarding the unification of filtering-smoothing regimes and the limitations of causal-gradient-based smoothing. These items represent significant conceptual shifts in data assimilation methodology rather than incremental performance improvements. I applied a strict filter to ensure only reusable, paradigm-level concepts were added to the vault.

### Approved Concepts
- ForcingDAS: The framework achieves a unified approach for filtering and smoothing in data assimilation by learning a joint-trajectory prior rather than frame-to-frame transitions.

### Approved Open Questions
- Unified Data Assimilation Frameworks: The authors identify this as a primary motivation for the unified ForcingDAS framework, contrasting it with existing specialized methods. This unification is crucial for efficient operational pipelines in weather and climate science.
- Causal-Only Smoothing Limitations: This is explicitly listed as a key limitation of the proposed ForcingDAS framework, directly impacting its potential performance in batch reanalysis tasks.

## Links

- [Abstract](https://arxiv.org/abs/2605.14285)
- [PDF](https://arxiv.org/pdf/2605.14285)

