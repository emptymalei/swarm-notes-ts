---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Single-stage joint diffusion of sky images and clear-sky index for ultra-short-term irradiance forecasting: what the frame-to-irradiance stage discards"
description: "This paper introduces a single-stage diffusion model for ultra-short-term solar irradiance forecasting that replaces the traditional cascaded design of video prediction followed by regression. By co-denoising sky images and the clear-sky index (CSI) in a single process, the model preserves critical information that is typically lost between stages in two-step architectures. Results on the SIRTA dataset show that the joint model significantly outperforms cascaded baselines and provides robust probabilistic forecasts (CRPS skill score of +0.34) even when historical irradiance measurements are unavailable at the input."
resource: "https://arxiv.org/abs/2610.21795"
tags:
  - "solar-power-forecasting"
  - "spatiotemporal-forecasting"
  - "probabilistic-forecasting"
  - "video-prediction"
  - "weather-forecasting"
  - "diffusion-models"
  - "time-series"
  - "computer-vision"
  - "ultra-short-term-forecasting"
timestamp: "2026-10-18T00:18:41Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Kanawut Suwandee"
  - literal: "Suwichaya Suwanwimolkul"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21795"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "joint-modal-diffusion"
    description: "A diffusion-based modeling paradigm where disparate modalities, such as video frames and scalar time-series indices, are co-denoised within a single generative process."
  - name: "denoised-preview-head"
    description: "An auxiliary task module that extracts features from the intermediate denoised estimate of the signal during the diffusion process rather than the current noisy state."
datasets:
  - name: "SIRTA"
    description: "Site Instrumental de Recherche par Télédétection Atmosphérique (SIRTA) dataset, providing high-frequency sky imagery and ground-based solar irradiance measurements for atmospheric research and forecasting."
open_questions:
  - name: "generative-point-accuracy-gap"
    description: "How can joint diffusion frameworks effectively integrate local sensor measurements to eliminate the point-accuracy (RMSE) gap currently held by deterministic networks, while maintaining superior probabilistic (CRPS) skill?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:18:41Z"
created_at: "2026-10-18T00:18:41Z"
---

# Single-stage joint diffusion of sky images and clear-sky index for ultra-short-term irradiance forecasting: what the frame-to-irradiance stage discards

**Authors**: Kanawut Suwandee, Suwichaya Suwanwimolkul
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21795](https://arxiv.org/abs/2610.21795)

## Summary

This paper introduces a single-stage diffusion model for ultra-short-term solar irradiance forecasting that replaces the traditional cascaded design of video prediction followed by regression. By co-denoising sky images and the clear-sky index (CSI) in a single process, the model preserves critical information that is typically lost between stages in two-step architectures. Results on the SIRTA dataset show that the joint model significantly outperforms cascaded baselines and provides robust probabilistic forecasts (CRPS skill score of +0.34) even when historical irradiance measurements are unavailable at the input.

## Key Contributions

- Proposed a single-stage diffusion framework that co-denoises future sky-image sequences and clear-sky index (CSI) values simultaneously, eliminating the need for a separate regression stage.
- Demonstrated that joint training recovers roughly 46 W/m² of RMSE accuracy that traditional cascaded pipelines (video-prediction then regression) discard.
- Achieved a skill score of +0.34 on CRPS against smart persistence on the SIRTA dataset without requiring measured irradiance as an input.
- Showed that while point accuracy is slightly lower than deterministic models with access to pyranometers, the diffusion approach provides superior probabilistic skill across all sky conditions.

## Limitations

The model's point accuracy (RMSE) is slightly lower than a deterministic network that has access to historical measured irradiance.

## Open Questions & Future Work

- [[generative-point-accuracy-gap]]

## Key Concepts

- [[joint-modal-diffusion]]: A diffusion-based modeling paradigm where disparate modalities, such as video frames and scalar time-series indices, are co-denoised within a single generative process.
- [[denoised-preview-head]]: An auxiliary task module that extracts features from the intermediate denoised estimate of the signal during the diffusion process rather than the current noisy state.

## Archivist Review

The approved concepts capture the core methodological shift proposed in the paper: moving from cascaded video prediction to a single-stage joint diffusion process. 'Joint Modal Diffusion' represents the high-level paradigm shift, while 'Denoised Preview Head' identifies the specific architectural mechanism used to bridge the gap between noisy generation and precise regression. The SIRTA dataset is a well-established benchmark in solar forecasting and merits inclusion. The open question addresses a critical performance trade-off identified in the results: the discrepancy between the probabilistic skill of diffusion models and the point-accuracy of sensor-augmented deterministic baselines.

### Approved Concepts
- Joint Modal Diffusion: It replaces the traditional cascaded 'predict-then-regress' pipeline, which is shown to discard significant information (46 W/m² RMSE loss) compared to joint modeling.
- Denoised Preview Head: By accessing the predicted clean signal ($x_0$) rather than the noisy latent ($x_t$), the model achieves better performance on auxiliary regression tasks without waiting for the full denoising cycle.

### Approved Open Questions
- Closing the Point-Accuracy Gap in Generative Forecasting: Grid integration requires both reliable uncertainty estimation and high point-prediction accuracy; current models often trade one for the other.

## Datasets

- [[SIRTA]]

## Links

- [Abstract](https://arxiv.org/abs/2610.21795)
- [PDF](https://arxiv.org/pdf/2610.21795)

