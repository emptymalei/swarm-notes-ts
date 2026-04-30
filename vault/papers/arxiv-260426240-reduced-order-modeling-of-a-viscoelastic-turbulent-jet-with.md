---
# CSL-compatible fields
title: "Reduced-order modeling of a viscoelastic turbulent jet with hybrid machine learning models"
author:
  - literal: "Christian Amor"
  - literal: "Adrián Corrochano"
  - literal: "Marco Edoardo Rosti"
  - literal: "Soledad Le Clainche"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26240"

# Custom fields
paper_id: "2604.26240"
paper_source: "arxiv"
domain: "fluid-dynamics"
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
processed_at: "2026-04-30T05:14:21Z"
created_at: "2026-04-30T05:14:21Z"
---

# Reduced-order modeling of a viscoelastic turbulent jet with hybrid machine learning models

**Authors**: Christian Amor, Adrián Corrochano, Marco Edoardo Rosti, Soledad Le Clainche
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26240](https://arxiv.org/abs/2604.26240)

## Summary

This paper addresses the computational intensity of simulating viscoelastic turbulent jets by developing a hybrid reduced-order model. The approach projects high-dimensional flow data into a compact subspace using proper orthogonal decomposition, then employs deep neural networks to evolve the mode coefficients over time. The results establish that this framework captures complex long-term statistics of the turbulent jet while providing significant computational efficiency, particularly when employing skip connections for better feature propagation.

## Key Contributions

- Introduces hybrid reduced-order modeling for viscoelastic turbulent jets, combining proper orthogonal decomposition (POD) with neural network time-series prediction.
- Demonstrates that skip connections significantly improve model depth, generalizability, and the accuracy of capturing small-scale dynamics in viscoelastic turbulent flows.
- Shows that the hybrid approach effectively maintains long-term statistical stability, enabling substantial computational speedup compared to full-order numerical simulations.

## Open Questions & Future Work

- [[balancing-interpretability-and-compression-in-turbulent-roms]]

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 0 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Open Questions
- Interpretability vs. compression in ROMs: This tension is a fundamental bottleneck in the design of efficient, robust, and physically grounded surrogates for high-dimensional chaotic systems.

### Rejected Candidates
- [concept] Hybrid reduced-order modeling (`hybrid-reduced-order-modeling`) - not_novel: This is a broad, established methodology in computational fluid dynamics rather than a specific novel contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.26240)
- [PDF](https://arxiv.org/pdf/2604.26240)

