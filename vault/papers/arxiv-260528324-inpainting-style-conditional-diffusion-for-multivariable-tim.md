---
# CSL-compatible fields
title: "Inpainting-Style Conditional Diffusion for Multivariable Time Series Forecasting"
author:
  - literal: "Kourosh Kiani"
  - literal: "S. M. Muyeen"
issued:
  date-parts:
    - [2026, 5, 27]
url: "https://arxiv.org/abs/2605.28324"

# Custom fields
paper_id: "2605.28324"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "diffusion-models"
  - "solar-power-forecasting"
architectures:
  []
datasets:
  - "gefcom2014"
concept_slugs:
  - "time-series-inpainting-diffusion"
dataset_slugs:
  - "gefcom2014"
skill: "TimeSeriesSkill"
processed_at: "2026-05-28T05:31:54Z"
created_at: "2026-05-28T05:31:54Z"
---

# Inpainting-Style Conditional Diffusion for Multivariable Time Series Forecasting

**Authors**: Kourosh Kiani, S. M. Muyeen
**Date**: 2026-05-27
**Paper ID**: [arxiv:2605.28324](https://arxiv.org/abs/2605.28324)

## Summary

This paper proposes an inpainting-style conditional diffusion framework for multivariable solar power forecasting by treating future values as missing regions in 2D temporal patches. The method employs a denoising diffusion probabilistic model (DDPM) to learn coherent future sequences conditioned on historical data within a U-Net architecture. By reformulating forecasting as a reconstruction problem, the model provides a flexible and robust mechanism for high-fidelity temporal predictions, demonstrating improved short-term accuracy on the GEFCom2014 dataset.

## Key Contributions

- Proposes a diffusion-based framework that reformulates multivariable solar power forecasting as an inpainting problem using 2D time-series patches.
- Introduces a mask-based conditional diffusion mechanism where historical observations condition the generative reconstruction of missing future time steps.
- Achieves superior short-term solar power forecasting performance on the GEFCom2014 benchmark compared to standard baselines.

## Key Concepts

- [[time-series-inpainting-diffusion]]: A conditional diffusion framework that treats future time-series values as missing regions to be reconstructed via iterative denoising.

## Archivist Review

I approved the core 'Time-series Inpainting Diffusion' concept, as treating forecasting as a masked inpainting task is a reusable methodological shift for generative time-series modeling. I also approved GEFCom2014 as a standard reusable benchmark dataset. Other candidates were rejected to maintain the strict novelty and reuse criteria of the vault.

### Approved Concepts
- Time-series Inpainting Diffusion: It introduces a paradigm shift in time-series forecasting by reinterpreting temporal extrapolation as a generative image inpainting task.

## Datasets

- [[gefcom2014]]

## Links

- [Abstract](https://arxiv.org/abs/2605.28324)
- [PDF](https://arxiv.org/pdf/2605.28324)

