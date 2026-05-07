---
# CSL-compatible fields
title: "A Generalized Framework of Antisymmetric Polyspectral Indices for Identifying High-Order Neural Interactions"
author:
  - literal: "Alessio Basti"
  - literal: "Rikkert Hindriks"
  - literal: "Ruggero Freddi"
  - literal: "Gian Luca Romani"
  - literal: "Vittorio Pizzella"
  - literal: "Guido Nolte"
  - literal: "Laura Marzetti"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04636"

# Custom fields
paper_id: "2605.04636"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "antisymmetric-cross-polyspectral-indices"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:33Z"
created_at: "2026-05-07T05:15:33Z"
---

# A Generalized Framework of Antisymmetric Polyspectral Indices for Identifying High-Order Neural Interactions

**Authors**: Alessio Basti, Rikkert Hindriks, Ruggero Freddi, Gian Luca Romani, Vittorio Pizzella, Guido Nolte, Laura Marzetti
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04636](https://arxiv.org/abs/2605.04636)

## Summary

This paper introduces a generalized framework of antisymmetric cross-polyspectral indices to characterize high-order neural interactions across multiple frequencies. The proposed indices quantify harmonic dependencies where a target frequency is the sum of multiple component frequencies, providing inherent robustness to instantaneous volume conduction artifacts. The approach is theoretically grounded, validated through simulation, and demonstrated on empirical EEG data to uncover previously undetected multi-frequency dependencies. These indices offer a promising path toward precision neuro-modulation by enabling targeted monitoring of specific neural network interactions.

## Key Contributions

- Proposes a generalized family of antisymmetric cross-polyspectral indices for identifying high-order frequency couplings where f_N = sum(f_i).
- Establishes theoretical robustness against spurious zero-lag artifacts commonly induced by volume conduction.
- Validates the framework through cubic nonlinearity simulations and demonstrates superior detection of dependencies in empirical EEG recordings compared to standard methods.

## Open Questions & Future Work

- [[real-time-estimation-of-polyspectral-indices]]

## Key Concepts

- [[antisymmetric-cross-polyspectral-indices]]: A class of spectral metrics designed to identify and quantify genuine high-order multi-frequency interactions while remaining robust to instantaneous signal mixing.

## Archivist Review

I approved the core framework (antisymmetric cross-polyspectral indices) as a novel, robust tool for high-order time-series dependency analysis that successfully addresses signal mixing artifacts. I also approved one open question concerning the statistical trade-offs required for real-time estimation, as this is a specific, well-defined bottleneck for clinical/control applications. I rejected the generalizability question because it is a routine, boilerplate invitation for more data/larger cohorts.

### Approved Concepts
- Antisymmetric Cross-Polyspectral Indices: They address the limitations of conventional metrics in identifying genuine higher-order frequency couplings amidst spurious volume conduction artifacts, a central problem in multi-channel time-series analysis.

### Approved Open Questions
- Real-time polyspectral estimation trade-offs: Temporal resolution is a primary hurdle for transitioning these theoretical metrics into actionable tools for adaptive, personalized interventions like multi-site TMS.

## Links

- [Abstract](https://arxiv.org/abs/2605.04636)
- [PDF](https://arxiv.org/pdf/2605.04636)

