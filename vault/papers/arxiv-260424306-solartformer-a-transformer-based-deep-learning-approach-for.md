---
# CSL-compatible fields
title: "SolarTformer: A Transformer Based Deep Learning Approach for Short Term Solar Power Forecasting"
author:
  - literal: "Ankan Basu"
  - literal: "Jyotiraditya Roy"
  - literal: "Aditya Datta"
  - literal: "Prayas Sanyal"
  - literal: "Sumanta Banerjee"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24306"

# Custom fields
paper_id: "2604.24306"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-28T05:14:47Z"
created_at: "2026-04-28T05:14:47Z"
---

# SolarTformer: A Transformer Based Deep Learning Approach for Short Term Solar Power Forecasting

**Authors**: Ankan Basu, Jyotiraditya Roy, Aditya Datta, Prayas Sanyal, Sumanta Banerjee
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24306](https://arxiv.org/abs/2604.24306)

## Summary

SolarTformer is a Transformer-based deep learning model designed for short-term solar power output prediction using meteorological data. The model utilizes self-attention mechanisms to effectively capture complex temporal dependencies and spatial variability in irradiance patterns. By integrating power station-specific metadata, it achieves enhanced generalizability across diverse locations and panel configurations, outperforming traditional forecasting baselines.

## Key Contributions

- Introduces SolarTformer, an attention-based architecture specifically designed to capture temporal and spatial dependencies in solar power forecasting.
- Demonstrates superior performance over traditional baseline models by incorporating power station-specific metadata for enhanced generalization across sites and configurations.
- Validates the robustness of the proposed model under varying atmospheric conditions, specifically showing improved accuracy for both clear and cloudy days.

## Open Questions & Future Work

- [[edge-deployment-of-transformer-forecasting-models]]
- [[interpretability-of-transformer-based-forecasting]]

## Archivist Review

The paper applies standard Transformer architectures to solar forecasting and integrates metadata as a local implementation strategy. I rejected the concept 'SolarTformer' as it is a paper-specific model without sufficient novelty for a standalone note. The open questions were approved as they address significant bottlenecks for applying high-performance models in real-world grid infrastructure.

### Approved Open Questions
- Edge Deployment of Transformers: This is a significant barrier to the real-world adoption of high-performance transformer models in decentralized energy management.
- Explainability of Transformer Models: Model interpretability is essential for building trust and ensuring the reliability of automated grid management systems.

### Rejected Candidates
- [concept] SolarTformer (`solartformer`) - paper_local: SolarTformer is a paper-specific model implementation without a novel, reusable methodological contribution beyond standard transformer usage.

## Links

- [Abstract](https://arxiv.org/abs/2604.24306)
- [PDF](https://arxiv.org/pdf/2604.24306)

