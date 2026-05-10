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
domain: "computer-vision"
tags:
  - "physics-informed-meta-learning"
  - "remote-sensing"
  - "environmental-monitoring"
  - "biogeochemical-retrieval"
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-aware-meta-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:21:14Z"
created_at: "2026-05-10T05:21:14Z"
---

# Region-adaptable retrieval of coastal biogeochemical parameters from near-surface hyperspectral remote sensing reflectance using physics-aware meta-learning

**Authors**: Yiqing Guo, Nagur R. C. Cherukuru, Eric A. Lehmann, S. L. Kesav Unnithan, Tim J. Malthus, Gemma Kerrisk, Xiubin Qi, Faisal Islam, Tisham Dhar, Mark J. Doubell
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05623](https://arxiv.org/abs/2605.05623)

## Summary

This paper addresses the challenge of generalizing biogeochemical (BGC) parameter retrieval across diverse coastal water bodies by proposing a two-stage physics-aware meta-learning framework. The approach first pretrains a region-agnostic base model on synthetic data generated from bio-optical forward models, followed by fine-tuning on regional in situ hyperspectral reflectance samples. Experimental validation across five distinct Australian coastal sites confirms that the method captures regional bio-optical differences and outperforms existing benchmark retrieval models. The findings demonstrate that the integrated approach accurately tracks both the magnitude and temporal dynamics of BGC parameters.

## Key Contributions

- Proposed a two-stage physics-aware meta-learning framework that bridges the gap between regional bio-optical variations for improved BGC parameter retrieval.
- Demonstrated the effectiveness of using bio-optical forward models to generate synthetic datasets for pretraining models with broad geographic representativeness.
- Achieved state-of-the-art performance on BGC parameter retrieval across five geographically distinct Australian coastal sites compared to five benchmark models.

## Open Questions & Future Work

- [[global-validation-coastal-diversity]]
- [[satellite-hyperspectral-retrieval-adaptation]]

## Key Concepts

- [[physics-aware-meta-learning]]: A training framework that combines bio-optical forward models to generate synthetic data for meta-learning, enabling region-agnostic pretraining and subsequent region-specific adaptation.

## Archivist Review

The approved concept captures a powerful methodology for integrating physical knowledge into meta-learning, which is highly reusable for scientific sensing. The approved open questions address the critical hurdles of regional generalization and the scaling of such models from ground to satellite platforms, moving beyond simple 'need more data' boilerplate to specific methodological bottlenecks in physical remote sensing.

### Approved Concepts
- physics-aware-meta-learning: Provides the core mechanism for enabling region-agnostic pretraining followed by region-specific adaptation in aquatic remote sensing.

### Approved Open Questions
- Global Validation of Coastal Diversity: Ensuring global generalizability is the central requirement for these frameworks to move from site-specific tools to robust environmental monitoring systems.
- Satellite Hyperspectral Retrieval Adaptation: Transitioning to satellite platforms is the primary bottleneck for achieving large-scale, high-spatiotemporal resolution water quality monitoring.

## Links

- [Abstract](https://arxiv.org/abs/2605.05623)
- [PDF](https://arxiv.org/pdf/2605.05623)

