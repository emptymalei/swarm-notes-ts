---
# CSL-compatible fields
title: "ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing"
author:
  - literal: "Yixuan Jia"
  - literal: "Siyi Chen"
  - literal: "Yida Pan"
  - literal: "Xiao Li"
  - literal: "Lianghe Shi"
  - literal: "Chanyong Jung"
  - literal: "Haijie Yuan"
  - literal: "Ismail Alkhouri, Yue Cynthia Wu, Saiprasad Ravishankar, Jeffrey A Fessler, Qing Qu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14285"

# Custom fields
paper_id: "2605.14285"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "diffusion-models"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "forcingdas"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:13:35Z"
created_at: "2026-05-16T05:13:35Z"
---

# ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing

**Authors**: Yixuan Jia, Siyi Chen, Yida Pan, Xiao Li, Lianghe Shi, Chanyong Jung, Haijie Yuan, Ismail Alkhouri, Yue Cynthia Wu, Saiprasad Ravishankar, Jeffrey A Fessler, Qing Qu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14285](https://arxiv.org/abs/2605.14285)

## Summary

ForcingDAS is a robust data assimilation framework that addresses the accumulation of errors in long-horizon dynamical system tracking by learning a joint-trajectory prior rather than iterative frame-to-frame transitions. By applying Diffusion Forcing with independent per-frame noise, the framework enables a single trained model to perform both real-time nowcasting and retrospective smoothing via adjustable inference-time scheduling. Experimental results across diverse domains, including atmospheric state estimation, demonstrate superior performance and stability compared to specialized baseline methods.

## Key Contributions

- Introduces ForcingDAS, a unified data assimilation framework that eliminates the need for distinct filtering and smoothing pipelines.
- Replaces brittle frame-to-frame transition models with joint-trajectory priors, significantly mitigating error accumulation over long horizons.
- Achieves state-of-the-art performance on 2D Navier-Stokes and global atmospheric state estimation benchmarks by leveraging inference-time scheduling to adapt across the filtering-smoothing spectrum.

## Open Questions & Future Work

- [[unified-da-inference-regimes]]
- [[robust-da-non-markovian-systems]]

## Key Concepts

- [[forcingdas]]: A unified data assimilation framework utilizing diffusion forcing with independent frame-wise noise levels to learn joint-trajectory priors.

## Archivist Review

The submission identifies a significant advance in data assimilation by replacing iterative frame-to-frame models with trajectory-based diffusion forcing. I have approved the framework itself and the two open questions addressing the unification of DA inference regimes and the problem of non-Markovian observation sequences, as these are foundational challenges in scientific time-series forecasting. No datasets were approved as the candidates were either generic or insufficiently documented as standalone benchmarks.

### Approved Concepts
- ForcingDAS: Represents a novel paradigm for unified data assimilation that handles both filtering and smoothing without separate models.

### Approved Open Questions
- Unified Data Assimilation Regimes: Unifying DA regimes allows for more efficient model training, facilitates the creation of foundation models for scientific discovery, and avoids the redundant overhead of maintaining multiple specialized pipelines.
- Robust DA in Non-Markovian Systems: Robustness to non-Markovian data is essential for real-world scientific applications like weather and climate forecasting where full state observability is impossible.

## Links

- [Abstract](https://arxiv.org/abs/2605.14285)
- [PDF](https://arxiv.org/pdf/2605.14285)

