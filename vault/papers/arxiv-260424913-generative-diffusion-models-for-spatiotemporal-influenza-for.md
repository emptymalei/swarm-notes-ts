---
# CSL-compatible fields
title: "Generative diffusion models for spatiotemporal influenza forecasting"
author:
  - literal: "Joseph Lemaitre"
  - literal: "Justin Lessler"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24913"

# Custom fields
paper_id: "2604.24913"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "generative-models"
  - "diffusion-models"
  - "forecasting"
  - "epidemiology"
architectures:
  []
datasets:
  - "cdc-flusight-challenge"
concept_slugs:
  - "influpaint"
dataset_slugs:
  - "cdc-flusight-challenge"
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:42Z"
created_at: "2026-04-29T05:12:42Z"
---

# Generative diffusion models for spatiotemporal influenza forecasting

**Authors**: Joseph Lemaitre, Justin Lessler
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24913](https://arxiv.org/abs/2604.24913)

## Summary

Influpaint leverages denoising diffusion probabilistic models to capture complex spatiotemporal dynamics in influenza incidence by representing disease trajectories as image data. The model treats forecasting as a conditional inpainting task, allowing it to generate diverse and realistic epidemic projections from partial historical data. Empirical results demonstrate that training on a hybrid mixture of surveillance and simulated trajectories yields superior performance, effectively matching or exceeding leading ensemble-based benchmarks.

## Key Contributions

- Introduced Influpaint, a diffusion-based framework that formulates spatiotemporal epidemic forecasting as a conditional image inpainting task.
- Demonstrated that hybrid training on 30% surveillance and 70% simulated data optimizes performance for complex disease dynamics.
- Achieved competitive forecasting accuracy compared to ensemble baselines and provided validated real-time performance during the 2023-2025 CDC FluSight challenges.

## Open Questions & Future Work

- [[diffusion-forecasting-reporting-delays]]
- [[diffusion-model-interpretability]]

## Key Concepts

- [[influpaint]]: A diffusion-based forecasting framework that treats spatiotemporal incidence data as images to perform conditional generation via inpainting.

## Archivist Review

The paper introduces a compelling approach to epidemiological forecasting by treating disease incidence as image-based spatiotemporal data for conditional diffusion. I approved the core concept 'Influpaint' for its novel framing of the problem. For datasets, I standardized the CDC FluSight reference to ensure vault consistency. The two approved open questions highlight critical, actionable limitations—reporting delays and interpretability—that are common to generative forecasting models in high-stakes domains.

### Approved Concepts
- Influpaint: It introduces a novel framing of spatiotemporal epidemiological forecasting as a conditional image inpainting task, shifting disease dynamics into a visual representation space.

### Approved Open Questions
- Diffusion Reporting Delay Handling: Inaccurate handling of data revisions leads to biased projections in public health, making this a critical reliability bottleneck for real-time model deployment.
- Diffusion Forecast Interpretability: Providing mechanistic clarity is essential for decision-makers to justify public health interventions based on machine-generated forecasts.

## Datasets

- [[cdc-flusight-challenge]]

## Links

- [Abstract](https://arxiv.org/abs/2604.24913)
- [PDF](https://arxiv.org/pdf/2604.24913)

