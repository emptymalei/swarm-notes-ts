---
# CSL-compatible fields
title: "Region-adaptable retrieval of coastal biogeochemical parameters from near-surface hyperspectral remote sensing reflectance using physics-aware meta-learning"
author:
  - literal: "Yiqing Guo"
  - literal: "Nagur R. C. Cherukuru"
  - literal: "Eric A. Lehmann"
  - literal: "S. L. Kesav Unnithan"
  - literal: "Tim J. Malthus"
  - literal: "Gemma Kerrisk"
  - literal: "Xiubin Qi"
  - literal: "Faisal Islam"
  - literal: "Tisham Dhar"
  - literal: "Mark J. Doubell"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05623"

# Custom fields
paper_id: "2605.05623"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "physics-informed-machine-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-aware-meta-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:13:10Z"
created_at: "2026-05-09T05:13:10Z"
---

# Region-adaptable retrieval of coastal biogeochemical parameters from near-surface hyperspectral remote sensing reflectance using physics-aware meta-learning

**Authors**: Yiqing Guo, Nagur R. C. Cherukuru, Eric A. Lehmann, S. L. Kesav Unnithan, Tim J. Malthus, Gemma Kerrisk, Xiubin Qi, Faisal Islam, Tisham Dhar, Mark J. Doubell
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05623](https://arxiv.org/abs/2605.05623)

## Summary

This paper addresses the challenge of generalizing coastal biogeochemical (BGC) parameter retrieval across diverse water bodies by proposing a two-stage physics-aware meta-learning framework. The first stage uses a bio-optical forward model to generate a synthetic dataset for pretraining, while the second stage fine-tunes the base model using local in situ hyperspectral reflectance (Rrs) and BGC measurements. Experimental evaluation across five geographically distinct Australian sites demonstrates that the proposed method significantly outperforms standard benchmark models in both accuracy and the capture of temporal dynamics.

## Key Contributions

- Introduced a two-stage physics-aware meta-learning framework for BGC parameter retrieval that adapts to local bio-optical variability.
- Demonstrated that a synthetic dataset generated from bio-optical forward models provides physical plausibility and alignment with in situ coastal observations.
- Achieved superior performance in retrieving biogeochemical parameters compared to five standard benchmark models across five distinct Australian coastal sites.

## Open Questions & Future Work

- [[coastal-bgc-generalization-global-diversity]]
- [[satellite-hyperspectral-adaptation-bottlenecks]]

## Key Concepts

- [[physics-aware-meta-learning]]: A two-stage approach combining synthetic data generation from bio-optical models with meta-learning to adapt parameter retrieval to local environmental conditions.

## Archivist Review

I approved the concept of Physics-Aware Meta-Learning as it provides a valuable template for using physics-informed synthetic data to solve distribution-shift problems in localized regression. I also approved two research questions focused on scaling these techniques to global environments and satellite-based observational conditions, which represent the primary bottleneck in scaling remote sensing retrieval. All other items were rejected for being overly domain-specific or lacking the generality required for the knowledge vault.

### Approved Concepts
- Physics-Aware Meta-Learning: Integrates bio-optical forward modeling with meta-learning to generalize retrieval algorithms across geographically distinct coastal waters.

### Approved Open Questions
- Global Generalization of BGC Retrieval: Establishing the global transferability of BGC retrieval models is essential for developing standardized, cost-effective water quality monitoring tools that can operate effectively across disparate geographic regions.
- Satellite-based Hyperspectral Retrieval Adaptation: Developing accurate satellite-based BGC retrieval is the fundamental bottleneck to moving from local, point-based observations to regional and global-scale, continuous water quality monitoring.

## Links

- [Abstract](https://arxiv.org/abs/2605.05623)
- [PDF](https://arxiv.org/pdf/2605.05623)

