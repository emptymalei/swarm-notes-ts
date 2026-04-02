---
# CSL-compatible fields
title: "Super-Resolving Coarse-Resolution Weather Forecasts With Flow Matching"
author:
  - literal: "Aymeric Delefosse"
  - literal: "Anastase Charantonis"
  - literal: "Dominique Béréziat"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00897"

# Custom fields
paper_id: "2604.00897"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "generative-super-resolution-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:37:39Z"
created_at: "2026-04-02T05:37:39Z"
---

# Super-Resolving Coarse-Resolution Weather Forecasts With Flow Matching

**Authors**: Aymeric Delefosse, Anastase Charantonis, Dominique Béréziat
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00897](https://arxiv.org/abs/2604.00897)

## Summary

This paper addresses the computational expense of high-resolution weather forecasting by decoupling forecast generation from spatial refinement. The authors propose a modular framework that uses flow matching to apply generative super-resolution as a post-processing step on coarse-resolution trajectories. By formulating the process as a residual-based stochastic inverse problem, the model effectively reconstructs unresolved variability while maintaining the large-scale physical consistency of the original forecasts. Evaluation confirms that the framework achieves competitive probabilistic skill at 0.25° resolution against operational baselines.

## Key Contributions

- Introduces a modular super-resolution framework that decouples high-resolution generation from coarse-resolution forecasting using flow matching.
- Demonstrates that the residual flow matching formulation preserves large-scale physical structure while successfully reconstructing unresolved small-scale variability.
- Achieves 0.25° resolution forecast skill comparable to operational ensemble baselines with significantly lower training requirements than end-to-end high-resolution models.

## Open Questions & Future Work

- [[nwp-consistent-super-resolution]]

## Key Concepts

- [[generative-super-resolution-forecasting]]: A modular post-processing framework that uses flow matching-based generative super-resolution to enhance the spatial resolution of coarse weather forecasts.

## Archivist Review

I approved the core concept of decoupling forecasting from super-resolution via flow matching, as this is a high-impact architectural pattern in spatiotemporal forecasting. I also approved the open question regarding NWP-consistency, as it captures the fundamental tension between reanalysis-trained generative models and operational forecasting requirements. Other candidate open questions were rejected as they leaned toward routine engineering optimization rather than fundamental research bottlenecks.

### Approved Concepts
- Generative Super-Resolution Forecasting: Decouples the computational burden of high-resolution forecasting from coarse-resolution models, offering a scalable post-processing alternative to end-to-end high-resolution models.

### Approved Open Questions
- NWP-Consistent Generative Super-Resolution: Crucial for bridging the gap between ML-based super-resolution models and operational forecasting systems where distribution shift in spectral properties exists.

## Links

- [Abstract](https://arxiv.org/abs/2604.00897)
- [PDF](https://arxiv.org/pdf/2604.00897)

