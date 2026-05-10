---
# CSL-compatible fields
title: "End-to-End Identifiable and Consistent Recurrent Switching Dynamical Systems"
author:
  - literal: "Carles Balsells-Rodas"
  - literal: "Zhengrui Xiang"
  - literal: "Xavier Sumba"
  - literal: "Yingzhen Li"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06315"

# Custom fields
paper_id: "2605.06315"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "ωsds"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:18:48Z"
created_at: "2026-05-10T05:18:48Z"
---

# End-to-End Identifiable and Consistent Recurrent Switching Dynamical Systems

**Authors**: Carles Balsells-Rodas, Zhengrui Xiang, Xavier Sumba, Yingzhen Li
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06315](https://arxiv.org/abs/2605.06315)

## Summary

This paper addresses the challenge of learning identifiable latent representations for sequential data governed by regime-switching dynamics. The authors provide a theoretical framework for identifying recurrent nonlinear switching systems under relaxed assumptions. They introduce ΩSDS, a flow-based estimator that avoids the approximation biases inherent in standard VAE approaches by performing exact likelihood optimization through expectation-maximisation. Empirical results show that the method yields better disentanglement and more robust dynamic forecasting.

## Key Contributions

- Establishes theoretical identifiability conditions for a broad class of recurrent nonlinear switching dynamical systems.
- Introduces ΩSDS, a flow-based estimator that circumvents VAE approximation gaps by utilizing exact likelihood optimization via expectation-maximisation.
- Demonstrates superior latent structure disentanglement and improved forecasting accuracy on both synthetic and real-world time-series benchmarks.

## Key Concepts

- [[ωsds]]: A flow-based estimator for recurrent nonlinear switching dynamical systems that utilizes expectation-maximisation for exact likelihood optimization.

## Archivist Review

The paper makes a clear theoretical and methodological contribution to the field of identifiable latent representations for switching dynamical systems. ΩSDS is approved as it provides a novel, reusable estimator architecture combining flow-based modeling with expectation-maximisation. No datasets or open questions were proposed, and the contribution is self-contained and impactful for time-series forecasting.

### Approved Concepts
- ΩSDS: It is the core methodological contribution enabling exact likelihood-based identification of regime-switching dynamics in recurrent systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.06315)
- [PDF](https://arxiv.org/pdf/2605.06315)

