---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "StochLOB: Heavy-Tailed Score Matching for Robust Limit Order Book Trend Prediction"
description: "StochLOB introduces a robust score-matching framework specifically designed for limit order book (LOB) trend prediction by addressing the heavy-tailed and bursty nature of financial order flows. By replacing standard Brownian Gaussian noise in the forward diffusion process with jump-Lévy and clipped alpha-stable noise, the model better captures market 'jumps' during training. At inference, the model remains deterministic, avoiding the overhead of reverse-time sampling while benefiting from a score target that naturally down-weights outliers. Experimental results on Coinbase and Feishu A-share data show that StochLOB improves performance in stress scenarios and maintains competitive forecasting accuracy compared to Gaussian baselines."
resource: "https://arxiv.org/abs/2610.21081"
tags:
  - "financial-time-series"
  - "time-series-forecasting"
  - "market-microstructure"
  - "stochastic-processes"
  - "robustness"
  - "generative-modeling"
  - "diffusion-models"
  - "heavy-tailed-distributions"
timestamp: "2026-10-18T00:25:34Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Arshia Abolghasemi"
  - literal: "Seyed Reza Tavakoli"
  - literal: "Parsa Naderi"
  - literal: "Nazanin Mirzaei"
  - literal: "Behrad Jahani"
  - literal: "Saba Yousefzadeh"
  - literal: "Tahereh Javaheri"
  - literal: "Mohammad Hosein Rohban"
  - literal: "Gholamali Aminian"
  - literal: "Ali Habibnia"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21081"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "stoch-lob"
    description: "A training-only score-matching framework for time-series forecasting that replaces standard Gaussian noise with heavy-tailed and jump-Lévy noise to better model bursty dynamics."
datasets:
  []
open_questions:
  - name: "dynamic-tail-index-adaptation"
    description: "Research is needed to determine how the parameters of heavy-tailed corruption, such as the alpha-stability index or jump intensity in Lévy processes, can be dynamically adjusted in real-time to account for regime shifts in market volatility and tail behavior."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:25:34Z"
created_at: "2026-10-18T00:25:34Z"
---

# StochLOB: Heavy-Tailed Score Matching for Robust Limit Order Book Trend Prediction

**Authors**: Arshia Abolghasemi, Seyed Reza Tavakoli, Parsa Naderi, Nazanin Mirzaei, Behrad Jahani, Saba Yousefzadeh, Tahereh Javaheri, Mohammad Hosein Rohban, Gholamali Aminian, Ali Habibnia
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21081](https://arxiv.org/abs/2610.21081)

## Summary

StochLOB introduces a robust score-matching framework specifically designed for limit order book (LOB) trend prediction by addressing the heavy-tailed and bursty nature of financial order flows. By replacing standard Brownian Gaussian noise in the forward diffusion process with jump-Lévy and clipped alpha-stable noise, the model better captures market 'jumps' during training. At inference, the model remains deterministic, avoiding the overhead of reverse-time sampling while benefiting from a score target that naturally down-weights outliers. Experimental results on Coinbase and Feishu A-share data show that StochLOB improves performance in stress scenarios and maintains competitive forecasting accuracy compared to Gaussian baselines.

## Key Contributions

- Proposed StochLOB, a score-matching framework that utilizes heavy-tailed corruption laws (jump-Lévy and clipped alpha-stable noise) instead of standard Brownian Gaussian noise.
- Developed a training-only noising process that allows for deterministic inference without the need for computationally expensive reverse-time diffusion sampling.
- Demonstrated that non-Gaussian score targets naturally weight residuals according to their latent corruption scale, improving robustness to market bursts and jumps.
- Achieved improved performance on realized tail-window stress diagnostics on Coinbase LOB data while remaining competitive on standard prediction horizons.

## Limitations

The framework is training-only and deterministic at inference, meaning it does not produce a full posterior distribution through sampling like traditional diffusion models.

## Open Questions & Future Work

- [[dynamic-tail-index-adaptation]]

## Key Concepts

- [[stoch-lob]]: A training-only score-matching framework for time-series forecasting that replaces standard Gaussian noise with heavy-tailed and jump-Lévy noise to better model bursty dynamics.

## Archivist Review

The approved concept, StochLOB, highlights a novel framework that bridges diffusion-based noising with robust deterministic forecasting, a technique highly relevant for heavy-tailed financial data. The open question on dynamic tail-index adaptation addresses the fundamental challenge of non-stationarity in market microstructure. Datasets were rejected as they describe data sources rather than curated, named benchmark datasets.

### Approved Concepts
- StochLOB: It enables robust training for financial time series without the inference-time cost of diffusion sampling, effectively down-weighting outliers by interpreting the score target as posterior expected corruption precision.

### Approved Open Questions
- Dynamic Tail-Index Adaptation in Financial SDEs: Financial markets exhibit non-stationarity where the 'heaviness' of tails can fluctuate significantly during crises or periods of high volatility; a fixed parameter approach is likely to be sub-optimal.

### Rejected Candidates
- [dataset] Coinbase LOB data (`coinbase-lob-data`) - generic: This refers to a data source (Coinbase) rather than a specific, versioned, and publicly named benchmark dataset.
- [dataset] Feishu A-share (`feishu-a-share`) - paper_local: This is a specific proprietary or local dataset used for a transfer study and is not recognized as a standalone reusable benchmark.

## Links

- [Abstract](https://arxiv.org/abs/2610.21081)
- [PDF](https://arxiv.org/pdf/2610.21081)

