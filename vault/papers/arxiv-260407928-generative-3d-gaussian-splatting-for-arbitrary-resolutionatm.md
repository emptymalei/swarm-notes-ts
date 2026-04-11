---
# CSL-compatible fields
title: "Generative 3D Gaussian Splatting for Arbitrary-ResolutionAtmospheric Downscaling and Forecasting"
author:
  - literal: "Tao Hana"
  - literal: "Zhibin Wen"
  - literal: "Zhenghao Chen"
  - literal: "Fenghua Lin"
  - literal: "Junyu Gao"
  - literal: "Song Guo"
  - literal: "Lei Bai"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07928"

# Custom fields
paper_id: "2604.07928"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "3d-gaussian-atmospheric-primitives"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:45:13Z"
created_at: "2026-04-11T04:45:13Z"
---

# Generative 3D Gaussian Splatting for Arbitrary-ResolutionAtmospheric Downscaling and Forecasting

**Authors**: Tao Hana, Zhibin Wen, Zhenghao Chen, Fenghua Lin, Junyu Gao, Song Guo, Lei Bai
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07928](https://arxiv.org/abs/2604.07928)

## Summary

GSSA-ViT is a novel framework for atmospheric forecasting and downscaling that treats grid points as 3D Gaussian primitives to overcome the resolution limitations of traditional NWP models. The model incorporates a scale-aware attention mechanism to capture cross-scale dependencies, facilitating arbitrary-resolution generation. Evaluated on ERA5 and CMIP6, the approach enables accurate, multi-scale prediction of 87 atmospheric variables while improving computational efficiency.

## Key Contributions

- Introduces GSSA-ViT, a framework that integrates generative 3D Gaussian splatting with scale-aware vision transformers for flexible atmospheric downscaling and forecasting.
- Enables arbitrary-resolution atmospheric output by treating latitude-longitude grid points as 3D Gaussian centers, reducing computational constraints of traditional NWP.
- Demonstrates superior performance over state-of-the-art baselines on ERA5 and CMIP6 datasets for forecasting 87 atmospheric variables.

## Open Questions & Future Work

- [[mitigating-autoregressive-error-accumulation-weather-emulation]]

## Key Concepts

- [[3d-gaussian-atmospheric-primitives]]: A spatial representation technique that models atmospheric grid points as learnable 3D Gaussians to facilitate continuous resolution adaptation.

## Archivist Review

I approved a concept capturing the core representation innovation (using 3D Gaussians for grid points) and a scoped version of the open question regarding autoregressive error accumulation. The model architecture name 'GSSA-ViT' was rejected as it is a specific implementation instance rather than a foundational concept. The datasets ERA5 and CMIP6 were rejected as they are routine, standard benchmarks in the field.

### Approved Concepts
- 3D Gaussian Atmospheric Primitives: Replaces rigid grid representations with continuous, parameterizable Gaussian primitives, enabling arbitrary-resolution forecasting which is a fundamental shift in atmospheric modeling.

### Approved Open Questions
- Mitigating Autoregressive Error Accumulation: This represents the primary performance bottleneck for data-driven atmospheric forecasting, limiting their ability to replace traditional physics-based systems in medium-range prediction.

### Rejected Candidates
- [concept] GSSA-ViT (`gssa-vit`) - paper_local: The specific model architecture is a paper-local instantiation of broader techniques (3D Gaussians + ViT) rather than a universally reusable concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.07928)
- [PDF](https://arxiv.org/pdf/2604.07928)

