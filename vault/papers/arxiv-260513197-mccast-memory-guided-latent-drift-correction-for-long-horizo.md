---
# CSL-compatible fields
title: "McCast: Memory-Guided Latent Drift Correction for Long-Horizon Precipitation Nowcasting"
author:
  - literal: "Penghui Wen"
  - literal: "Yu Luo"
  - literal: "Lintao Wang"
  - literal: "Mengwei He"
  - literal: "Patrick Filippi"
  - literal: "Thomas Francis Bishop"
  - literal: "Zhiyong Wang"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13197"

# Custom fields
paper_id: "2605.13197"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-forecasting"
  - "nowcasting"
  - "latent-space-modeling"
architectures:
  []
datasets:
  - "SEVIR"
  - "MeteoNet"
concept_slugs:
  - "drift-corrective-memory-bank-dcbank"
dataset_slugs:
  - "sevir"
  - "meteonet"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:24:33Z"
created_at: "2026-05-14T05:24:33Z"
---

# McCast: Memory-Guided Latent Drift Correction for Long-Horizon Precipitation Nowcasting

**Authors**: Penghui Wen, Yu Luo, Lintao Wang, Mengwei He, Patrick Filippi, Thomas Francis Bishop, Zhiyong Wang
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13197](https://arxiv.org/abs/2605.13197)

## Summary

McCast addresses the error accumulation problem in long-horizon precipitation nowcasting by shifting the focus from improving step-wise accuracy to correcting latent drift. The method employs a Drift-Corrective Memory Bank (DCBank) that uses temporally organized historical states to calibrate autoregressive trajectories. By explicitly refining the latent evolution during rollouts, McCast produces more physically plausible and coherent predictions compared to standard autoregressive baselines. The effectiveness of this approach is validated through state-of-the-art results on the SEVIR and MeteoNet datasets.

## Key Contributions

- Introduces McCast, a memory-guided latent drift correction framework that mitigates error accumulation in long-horizon precipitation nowcasting.
- Proposes the Drift-Corrective Memory Bank (DCBank), which explicitly computes and applies temporal drift corrections to calibrate autoregressive latent evolutions.
- Demonstrates state-of-the-art performance on the SEVIR and MeteoNet benchmarks, specifically excelling in long-horizon predictive coherence.

## Open Questions & Future Work

- [[long-horizon-drift-scaling]]
- [[physics-constrained-latent-correction]]

## Key Concepts

- [[drift-corrective-memory-bank-dcbank]]: A memory-guided module that estimates and applies temporally consistent drift corrections to latent states in autoregressive forecasting.

## Archivist Review

I have approved the core drift-correction mechanism (DCBank) and the associated datasets as they represent a notable shift from step-wise accuracy to explicit latent trajectory refinement in long-horizon forecasting. The open questions regarding drift scaling and physical constraints are significant, universal research challenges in deep weather and dynamical systems forecasting. I applied a strict filter to ensure only the primary contribution and the most central unresolved bottlenecks were recorded.

### Approved Concepts
- Drift-Corrective Memory Bank (DCBank): The central mechanism for addressing autoregressive error accumulation by explicitly correcting latent drift during rollouts.

### Approved Open Questions
- Long-horizon drift scaling limits: Evaluating the limit of memory-based drift correction is critical for extending nowcasting systems to longer temporal scales, which are essential for proactive disaster management.
- Physics-constrained latent correction: Enforcing physical consistency is a fundamental challenge in deep learning-based weather forecasting, preventing physically implausible predictions even when data-driven models achieve high statistical performance.

## Datasets

- [[sevir]]
- [[meteonet]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13197)
- [PDF](https://arxiv.org/pdf/2605.13197)

