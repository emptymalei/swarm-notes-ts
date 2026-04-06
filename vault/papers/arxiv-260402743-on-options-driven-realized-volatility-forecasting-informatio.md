---
# CSL-compatible fields
title: "On options-driven realized volatility forecasting: Information gains via rough volatility model"
author:
  - literal: "Zheqi Fan"
  - literal: "Meng Wang"
  - literal: "Yifan Ye"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02743"

# Custom fields
paper_id: "2604.02743"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:03:14Z"
created_at: "2026-04-06T05:03:14Z"
---

# On options-driven realized volatility forecasting: Information gains via rough volatility model

**Authors**: Zheqi Fan, Meng Wang, Yifan Ye
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02743](https://arxiv.org/abs/2604.02743)

## Summary

This paper investigates the predictive value of spot volatility estimators derived from rough stochastic volatility models for forecasting realized volatility. To overcome the computational challenges of large-scale options data, the authors develop a deep learning surrogate model for efficient volatility estimation. The resulting HAR-RV-RHeston framework consistently outperforms established benchmarks, including Heston, Bates, and SVCJ models, and the VIX index across horizons ranging from daily to one month.

## Key Contributions

- Proposes the HAR-RV-RHeston model, which incorporates spot volatility estimators derived from rough volatility models into the HAR framework to enhance realized volatility forecasting.
- Introduces a deep learning surrogate to replace computationally intensive estimation processes, enabling efficient processing of large-scale options panels for volatility inference.
- Demonstrates significant improvements in daily and multi-horizon (up to one month) volatility forecasting performance over traditional models like Heston, Bates, SVCJ, and the VIX index.

## Open Questions & Future Work

- [[computational-efficiency-quadratic-rough-heston]]

## Archivist Review

I approved the open question regarding the computational efficiency of the quadratic rough Heston model, as it highlights a specific bottleneck in financial time-series modeling. I rejected the model architectures and surrogates mentioned as they represent specific implementations of established modeling paradigms rather than novel concepts that would recur as standalone architectural patterns.

### Approved Open Questions
- Computational Efficiency of Quadratic Rough Heston: The quadratic rough Heston model is a significant advancement in quantitative finance that enables consistent joint calibration of equity and volatility markets. Bridging the gap between its theoretical superiority and its practical computational bottleneck is essential for the next generation of volatility forecasting models.

### Rejected Candidates
- [concept] HAR-RV-RHeston (`har-rv-rheston`) - paper_local: This is a specific model architecture instance rather than a foundational or widely reusable methodology.
- [concept] Deep learning surrogate for volatility inference (`deep-learning-surrogate-for-volatility-inference`) - not_novel: While useful, this is a standard application of deep learning surrogates for simulation or calibration; it does not represent a unique new concept deserving a standalone note.

## Links

- [Abstract](https://arxiv.org/abs/2604.02743)
- [PDF](https://arxiv.org/pdf/2604.02743)

