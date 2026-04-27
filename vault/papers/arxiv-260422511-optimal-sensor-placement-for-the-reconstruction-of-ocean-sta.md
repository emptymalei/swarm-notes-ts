---
# CSL-compatible fields
title: "Optimal sensor placement for the reconstruction of ocean states using differentiable Gumbel-Softmax sampling operator"
author:
  - literal: "Oscar Chapron"
  - literal: "Ronan Fablet"
  - literal: "Yann Stéphan"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22511"

# Custom fields
paper_id: "2604.22511"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "differentiable-adaptive-sensor-placement"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:11:27Z"
created_at: "2026-04-27T05:11:27Z"
---

# Optimal sensor placement for the reconstruction of ocean states using differentiable Gumbel-Softmax sampling operator

**Authors**: Oscar Chapron, Ronan Fablet, Yann Stéphan
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22511](https://arxiv.org/abs/2604.22511)

## Summary

This paper addresses the challenge of optimizing sparse observation networks in non-stationary geophysical fields. The authors propose a differentiable sensor placement framework that uses a Gumbel-Softmax operator to jointly learn an optimal sampling mask and reconstruction mapping given a specific sensor budget. Experiments on high-resolution ocean simulations demonstrate that the approach significantly outperforms uniform random strategies in Sea Surface Height reconstruction, while providing interpretable and robust sampling patterns.

## Key Contributions

- Introduces a differentiable framework using Gumbel-Softmax sampling to jointly optimize observation masks and reconstruction mappings under strict sensor budgets.
- Achieves significant performance gains in Sea Surface Height reconstruction, reducing RMSE from 0.1750 m to 0.0908 m and increasing explained variance by ~20% compared to random sampling.
- Demonstrates robust performance and interpretability, effectively targeting high-energy ocean features like eddies and fronts under forecast uncertainty.

## Open Questions & Future Work

- [[robustness-to-operational-forecast-uncertainty]]
- [[computational-efficiency-of-sampling-mask-optimization]]

## Key Concepts

- [[differentiable-adaptive-sensor-placement]]: A gradient-based framework utilizing Gumbel-Softmax sampling to jointly optimize probabilistic observation masks and reconstruction mappings.

## Archivist Review

I have approved the core methodological contribution of differentiable sensor placement, as it addresses a fundamental challenge in spatiotemporal observation design using a reusable gradient-based technique. The two open questions are approved because they capture critical, non-trivial bottlenecks (operational robustness and computational scaling) that are essential for the maturation of this research field. No datasets were approved as none were presented as novel, unique, or central enough to qualify as a named research artifact.

### Approved Concepts
- Differentiable Adaptive Sensor Placement: Provides a novel gradient-based approach to the discrete combinatorial problem of optimal sensor network design under budget constraints.

### Approved Open Questions
- Robustness to operational forecast uncertainty: This is critical for bridging the gap between Observing-System Simulation Experiments (OSSEs) and practical deployment in operational oceanography, where the accuracy of the sensor placement strategy is sensitive to the fidelity of forecast uncertainty models.
- Computational efficiency of sampling-mask optimization: High computational costs limit the ability to scale the framework to larger domains or to perform frequent, real-time re-optimization in operational environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.22511)
- [PDF](https://arxiv.org/pdf/2604.22511)

