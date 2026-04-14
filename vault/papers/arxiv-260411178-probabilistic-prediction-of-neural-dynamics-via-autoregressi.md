---
# CSL-compatible fields
title: "Probabilistic Prediction of Neural Dynamics via Autoregressive Flow Matching"
author:
  - literal: "Nicole Rogalla"
  - literal: "Yuzhen Qin"
  - literal: "Mario Senden"
  - literal: "Ahmed El-Gazzar"
  - literal: "Marcel van Gerven"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11178"

# Custom fields
paper_id: "2604.11178"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "algonauts-2025-fmri-dataset"
concept_slugs:
  - "autoregressive-flow-matching-afm"
dataset_slugs:
  - "algonauts-2025-fmri-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:04:09Z"
created_at: "2026-04-14T05:04:09Z"
---

# Probabilistic Prediction of Neural Dynamics via Autoregressive Flow Matching

**Authors**: Nicole Rogalla, Yuzhen Qin, Mario Senden, Ahmed El-Gazzar, Marcel van Gerven
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11178](https://arxiv.org/abs/2604.11178)

## Summary

This paper introduces Autoregressive Flow Matching (AFM), a generative framework for probabilistic forecasting of neural dynamics based on multimodal sensory input and past neural states. By modeling future neural activity as a temporally evolving process, the model improves upon existing non-autoregressive and linear baselines in predicting short-term parcel-wise BOLD activity. Evaluations on the Algonauts 2025 fMRI dataset confirm that autoregressive factorization and history-dependency are essential for effective neural response modeling and generalization. The findings highlight the potential for flow-based generative models in closed-loop neurotechnology.

## Key Contributions

- Introduces Autoregressive Flow Matching (AFM) as a generative approach for probabilistic forecasting of neural BOLD activity.
- Demonstrates superior performance over non-autoregressive baselines and general linear model (GLM) baselines on the Algonauts 2025 fMRI dataset.
- Provides evidence that incorporating past neural history via autoregressive factorization is a critical factor for achieving high-fidelity short-term prediction of cortical dynamics.

## Key Concepts

- [[autoregressive-flow-matching-afm]]: A generative forecasting framework that models dynamics by learning conditional distributions of future states through autoregressive flow-based transport.

## Archivist Review

I have approved the Autoregressive Flow Matching concept as a reusable generative forecasting framework. I rejected the Algonauts dataset as it is a specific, niche competition-based benchmark that does not meet the high bar for permanent, broadly relevant knowledge vault entries. No open questions were proposed, and none were identified that warranted inclusion.

### Approved Concepts
- Autoregressive Flow Matching (AFM): AFM provides a novel fusion of autoregressive temporal conditioning with transport-based generative modeling for probabilistic time-series forecasting.

### Rejected Candidates
- [dataset] Algonauts project 2025 challenge functional magnetic resonance imaging dataset (`algonauts-2025-fmri-dataset`) - low_impact: The dataset is a specific competition-based benchmark for neuroimaging and does not yet represent a broader, widely adopted, or highly generalizable benchmark in the forecasting literature.

## Datasets

- [[algonauts-2025-fmri-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11178)
- [PDF](https://arxiv.org/pdf/2604.11178)

