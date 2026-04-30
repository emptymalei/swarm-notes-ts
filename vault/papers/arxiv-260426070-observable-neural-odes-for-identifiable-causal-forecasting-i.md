---
# CSL-compatible fields
title: "Observable Neural ODEs for Identifiable Causal Forecasting in Continuous Time"
author:
  - literal: "Jennifer Wendland"
  - literal: "Nicolas Freitag"
  - literal: "Maik Kschischo"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.26070"

# Custom fields
paper_id: "2604.26070"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "causal-inference"
  - "continuous-time-forecasting"
  - "latent-state-modeling"
  - "neural-odes"
architectures:
  []
datasets:
  - "mimic-iv"
concept_slugs:
  - "observable-neural-odes"
dataset_slugs:
  - "mimic-iv"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:14:56Z"
created_at: "2026-04-30T05:14:56Z"
---

# Observable Neural ODEs for Identifiable Causal Forecasting in Continuous Time

**Authors**: Jennifer Wendland, Nicolas Freitag, Maik Kschischo
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.26070](https://arxiv.org/abs/2604.26070)

## Summary

This paper addresses the challenge of causal inference in continuous-time systems with hidden confounders by connecting control-theoretic observability to causal identifiability. The authors derive a continuous-time adjustment formula and propose Observable Neural ODEs (ObsNODEs), which enforce an observable normal form to ensure that latent states are reconstructible from observations. This approach allows for robust outcome prediction under alternative treatment trajectories, outperforming existing sequence models across several synthetic and real-world medical benchmarks.

## Key Contributions

- Establishes a theoretical link between control-theoretic observability and causal identifiability in latent state-space models with hidden confounders.
- Derives a continuous-time adjustment formula for potential outcome distributions using measurement models, latent dynamics, and latent state filtering.
- Introduces Observable Neural ODEs (ObsNODEs), achieving superior causal forecasting performance on synthetic cancer, semi-synthetic MIMIC-IV, and sepsis datasets.

## Open Questions & Future Work

- [[assumptions-validation-causal-forecasting]]
- [[uncertainty-quantification-causal-forecasts]]

## Key Concepts

- [[observable-neural-odes]]: A Neural ODE architecture constrained to an observable normal form that ensures latent state reconstructibility from observations for causal forecasting.

## Archivist Review

The paper introduces a formal control-theoretic approach to enforce identifiability in continuous-time latent models, which is a significant and reusable contribution to the causal forecasting literature. The concepts and open questions were selected based on their fundamental importance to long-term research in causal dynamics and uncertainty quantification. The MIMIC-IV dataset was approved as a standard benchmark in this specific domain of causal medical time-series analysis.

### Approved Concepts
- Observable Neural ODEs (ObsNODEs): The core methodological contribution providing a bridge between control-theoretic observability and causal identifiability in continuous-time latent dynamics.

### Approved Open Questions
- Assumptions in causal forecasting: This is critical because the validity of the causal identification depends on these structural assumptions; without empirical verification, the model's causal estimates in real-world environments could be biased or misleading.
- Uncertainty in causal forecasts: Providing confidence intervals or uncertainty bounds is essential for the clinical application of these models, as clinicians need to understand the reliability of predicted treatment outcomes to make safe medical decisions.

## Datasets

- [[mimic-iv]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26070)
- [PDF](https://arxiv.org/pdf/2604.26070)

