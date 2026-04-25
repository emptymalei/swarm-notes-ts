---
# CSL-compatible fields
title: "Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models"
author:
  - literal: "Aditya Sai Pranith Ayapilla"
  - literal: "Kazuya Miyashita"
  - literal: "Yuki Yasuda"
  - literal: "Ryo Onishi"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21180"

# Custom fields
paper_id: "2604.21180"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "diffusion-models"
  - "data-assimilation"
  - "uncertainty-estimation"
  - "super-resolution"
  - "fluid-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "diffsrda"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:55:03Z"
created_at: "2026-04-25T04:55:03Z"
---

# Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models

**Authors**: Aditya Sai Pranith Ayapilla, Kazuya Miyashita, Yuki Yasuda, Ryo Onishi
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21180](https://arxiv.org/abs/2604.21180)

## Summary

DiffSRDA is a novel probabilistic data assimilation framework that leverages denoising diffusion models to perform spatiotemporal super-resolution on chaotic fluid systems. By training on low-resolution forecasts and sparse high-resolution observations, it generates high-resolution ensemble analyses that quantify uncertainty without the computational overhead of running large high-resolution ensemble forecasts. Experiments on barotropic ocean jet instability show competitive performance with traditional EnKF methods, with additional benefits in computational efficiency and robustness to sensor-layout changes.

## Key Contributions

- Developed DiffSRDA, a diffusion-based framework that performs probabilistic spatiotemporal super-resolution data assimilation using only low-resolution forecasts.
- Demonstrated that DiffSRDA achieves reconstruction quality comparable to high-resolution Ensemble Kalman Filters (EnKF) while providing physically meaningful uncertainty estimates.
- Showed that DiffSRDA can achieve near-full-chain accuracy with very few reverse sampling steps and supports training-free adaptation to sensor-layout shifts via score-based guidance.

## Open Questions & Future Work

- [[scalability-of-reverse-diffusion-chains]]
- [[guidance-impact-on-uncertainty-calibration]]

## Key Concepts

- [[diffsrda]]: A probabilistic spatiotemporal super-resolution data assimilation framework that uses denoising diffusion models to generate high-resolution analyses from low-resolution forecasts and sparse observations.

## Archivist Review

I approved the core framework DiffSRDA as it represents a significant new approach to probabilistic data assimilation. The two open questions are approved because they address critical bottlenecks—computational scalability of reverse chains and the preservation of uncertainty calibration under inference-time guidance—which are central to deploying diffusion models in scientific and meteorological forecasting contexts. All other candidates were rejected as they were either paper-local or secondary considerations.

### Approved Concepts
- DiffSRDA: DiffSRDA introduces a novel integration of denoising diffusion models into the data assimilation paradigm, enabling probabilistic super-resolution without requiring repeated high-resolution model forecasts.

### Approved Open Questions
- Scalability of Reverse Diffusion Chains: Understanding the scalability of the number of diffusion steps to more realistic or complex physical systems is critical for determining the practical utility of diffusion-based data assimilation in operational meteorological and geophysical forecasting.
- Guidance Impact on Uncertainty Calibration: Ensuring that uncertainty quantification remains robust during inference-time model adaptations is vital for high-stakes decision-making scenarios, such as severe-weather forecasting, where inaccurate uncertainty estimates can lead to poor decision outcomes.

## Links

- [Abstract](https://arxiv.org/abs/2604.21180)
- [PDF](https://arxiv.org/pdf/2604.21180)

