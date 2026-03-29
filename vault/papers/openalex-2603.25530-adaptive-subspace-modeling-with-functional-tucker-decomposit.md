---
# CSL-compatible fields
title: "Adaptive Subspace Modeling With Functional Tucker Decomposition"
author:
  - literal: "Noah Steidle"
  - literal: "Joppe De Jonghe"
  - literal: "Mariya Ishteva"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25530"

# Custom fields
paper_id: "2603.25530"
paper_source: "openalex"
domain: "time-series"
tags:
  - "tensor decomposition"
  - "functional data analysis"
  - "kernel methods"
architectures:
  []
datasets:
  []
concept_slugs:
  - "functional-tucker-decomposition"
  - "rkhs-driven-tensor-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:17:52Z"
created_at: "2026-03-29T20:17:52Z"
---

# Adaptive Subspace Modeling With Functional Tucker Decomposition

**Authors**: Noah Steidle, Joppe De Jonghe, Mariya Ishteva
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25530](https://arxiv.org/abs/2603.25530)

## Summary

This paper introduces the Functional Tucker Decomposition (FTD) to address the information loss from discretizing continuous multidimensional data. The FTD embeds mode-wise continuity constraints by employing Reproducing Kernel Hilbert Spaces (RKHS) to model continuous latent modes, thereby preserving the multi-linear structure of the Tucker model while introducing adaptive representational power. This approach yields expressive factor descriptions that enable targeted subspace modeling, shown to be highly effective for domain-variant tensor classification tasks. Evaluations highlight its utility in hyperspectral imaging and multivariate time series analysis, showcasing the synergy between structural decomposition and functional adaptability.

## Key Contributions

- Introduction of the Functional Tucker Decomposition (FTD) which embeds mode-wise continuity constraints directly into the Tucker model structure.
- Utilization of Reproducing Kernel Hilbert Spaces (RKHS) to model continuous tensor modes adaptively without relying on a pre-defined basis.
- Demonstration of FTD's effectiveness in domain-variant tensor classification tasks, specifically in hyperspectral imaging and multivariate time series analysis.

## Limitations

The abstract does not explicitly state limitations, but the reliance on RKHS implies sensitivity to kernel choice and computational cost for very high-dimensional data.

## Open Questions & Future Work

- [[ftd-multiple-continuous-modes]]
- [[optimal-rkhs-design-point-selection]]
- [[transfer-continuity-constraint-to-tt-decomposition]]
- [[ftd-missing-unaligned-data]]

## Key Concepts

- [[functional-tucker-decomposition]]: A tensor decomposition method that embeds mode-wise continuity constraints using Reproducing Kernel Hilbert Spaces (RKHS) to model continuous data modes.
- [[rkhs-driven-tensor-modeling]]: Using Reproducing Kernel Hilbert Spaces (RKHS) to implicitly define and model continuous basis functions within a tensor decomposition framework.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 4 open question(s), and 0 dataset(s), with 0 rejected candidate note(s).

### Approved Concepts
- Functional Tucker Decomposition (FTD): It is the central novel mathematical framework proposed, integrating functional modeling (via RKHS) directly into the established Tucker tensor decomposition structure.
- RKHS-driven Tensor Modeling: The use of RKHS is the specific mechanism enabling continuity and adaptivity within the decomposition, a distinct approach from standard discrete tensor factorizations.

### Approved Open Questions
- Expand FTD to multiple continuous modes: Expanding to multiple continuous modes would significantly broaden the applicability of the FTD method to other domains characterized by multiple smoothly varying measurements, such as multi-sensor medical signal analysis.
- Optimal RKHS design point selection: Optimal selection of sampling points is critical for the stability and accuracy of RKHS-based models, and developing general strategies would provide a significant methodological advancement for functional data analysis.
- Transfer continuity constraint to TT decomposition: Applying functional modeling concepts to other popular decompositions like the Tensor Train decomposition could yield powerful new models for structured, continuous data where the low-rank structure of TT might be more appropriate than the full core tensor of TD.
- FTD adaptation for missing data: Addressing missing or unaligned functional data is a common practical challenge, and integrating solutions directly into the FTD framework would substantially increase its utility in real-world scenarios.

## Links

- [Abstract](https://arxiv.org/abs/2603.25530)
- [PDF](https://arxiv.org/pdf/2603.25530)

