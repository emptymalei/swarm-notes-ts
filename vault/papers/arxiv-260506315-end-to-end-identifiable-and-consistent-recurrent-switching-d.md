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
domain: "nlp"
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
processed_at: "2026-05-09T05:10:40Z"
created_at: "2026-05-09T05:10:40Z"
---

# End-to-End Identifiable and Consistent Recurrent Switching Dynamical Systems

**Authors**: Carles Balsells-Rodas, Zhengrui Xiang, Xavier Sumba, Yingzhen Li
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06315](https://arxiv.org/abs/2605.06315)

## Summary

This paper addresses the challenge of learning identifiable latent representations in sequential data with regime-switching dynamics. It introduces ΩSDS, a flow-based estimator that avoids the approximation gaps common in VAE-based approaches by enabling exact likelihood optimization through expectation-maximisation. The authors provide theoretical proofs for identifiability under flexible assumptions and show that their model outperforms variational alternatives in both latent disentanglement and predictive performance.

## Key Contributions

- Establishes theoretical identifiability for a broad class of recurrent nonlinear switching dynamical systems under flexible assumptions.
- Introduces ΩSDS, a flow-based estimator that replaces VAE-based approaches with exact likelihood optimization using expectation-maximisation.
- Demonstrates superior disentanglement of latent structures and improved dynamic forecasting accuracy compared to variational baselines on synthetic and real-world datasets.

## Key Concepts

- [[ωsds]]: A flow-based estimator for recurrent switching dynamical systems that enables exact likelihood optimization via expectation-maximisation.

## Archivist Review

I approved the core estimator ΩSDS, as it represents a significant methodological shift from standard variational approaches (VAEs) to exact likelihood optimization for recurrent switching dynamical systems. I rejected other potential candidates as they were either local implementation details or already represented by general dynamical system terminology. The selection focuses on the central contribution that provides a new paradigm for learning identifiable representations in sequential regime-switching regimes.

### Approved Concepts
- ΩSDS: It is the primary model introduced to address identifiability and consistent likelihood optimization in switching dynamical systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.06315)
- [PDF](https://arxiv.org/pdf/2605.06315)

