---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Probabilistic AI models outperform numerical weather prediction models on record breaking heat extremes"
description: "This paper challenges the prevailing belief that physics-based numerical weather prediction (NWP) models are superior to AI weather prediction (AIWP) models for extreme events. By conducting a probabilistic evaluation, the authors show that AIWP models actually outperform the ECMWF IFS ensemble in forecasting global heat extremes and record-breaking events. The study identifies that previous conclusions regarding AIWP's poor performance on extremes were largely artifacts of deterministic verification choices, and that probabilistic models offer better tail calibration and lower miss rates."
resource: "https://arxiv.org/abs/2610.20519"
tags:
  - "weather-forecasting"
  - "meteorology"
  - "extreme-weather-forecasting"
  - "probabilistic-forecasting"
  - "benchmarking"
  - "climate-modeling"
  - "time-series-forecasting"
timestamp: "2026-10-18T00:31:39Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jakob Benjamin Wessel"
  - literal: "Fiona Spuler"
  - literal: "Christopher A. T. Ferro"
  - literal: "Marlene Kretschmer"
  - literal: "Sebastian Sippel"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20519"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "probabilistic-aiwp"
    description: "Weather forecasting systems that leverage AI architectures to produce probability distributions rather than point estimates, enabling better quantification of extreme risks."
  - name: "record-breaking-extreme-forecasting"
    description: "The prediction of meteorological events that exceed historical bounds, representing a primary challenge for machine learning models trained on historical data."
datasets:
  []
open_questions:
  - name: "aiwp-out-of-distribution-extremes"
    description: "To what extent can AIWP models maintain forecasting skill for 'unprecedented' record-breaking events that fall significantly outside the range of their training distributions, particularly under accelerating climate change?"
  - name: "probabilistic-aiwp-variable-generalization"
    description: "Do the probabilistic advantages of AIWP seen in thermal extremes generalize to more stochastic and localized variables like extreme precipitation?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:31:39Z"
created_at: "2026-10-18T00:31:39Z"
---

# Probabilistic AI models outperform numerical weather prediction models on record breaking heat extremes

**Authors**: Jakob Benjamin Wessel, Fiona Spuler, Christopher A. T. Ferro, Marlene Kretschmer, Sebastian Sippel
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20519](https://arxiv.org/abs/2610.20519)

## Summary

This paper challenges the prevailing belief that physics-based numerical weather prediction (NWP) models are superior to AI weather prediction (AIWP) models for extreme events. By conducting a probabilistic evaluation, the authors show that AIWP models actually outperform the ECMWF IFS ensemble in forecasting global heat extremes and record-breaking events. The study identifies that previous conclusions regarding AIWP's poor performance on extremes were largely artifacts of deterministic verification choices, and that probabilistic models offer better tail calibration and lower miss rates.

## Key Contributions

- Demonstrated that probabilistic AI weather prediction (AIWP) models outperform the state-of-the-art ECMWF IFS ensemble in forecasting heat extremes globally.
- Provided empirical evidence that AIWP models exhibit superior tail calibration and a lower rate of missed record-breaking events compared to raw and post-processed NWP.
- Identified a critical evaluation bias where deterministic verification methods unfairly penalize AIWP models when assessing extreme events.
- Validated the superiority of AIWP models for extremes using station-level ground observations across all considered lead times.

## Limitations

The study focuses primarily on thermal (heat) extremes; performance on other high-gradient variables like precipitation or extreme wind speeds is not evaluated.

## Open Questions & Future Work

- [[aiwp-out-of-distribution-extremes]]
- [[probabilistic-aiwp-variable-generalization]]

## Key Concepts

- [[probabilistic-aiwp]]: Weather forecasting systems that leverage AI architectures to produce probability distributions rather than point estimates, enabling better quantification of extreme risks.
- [[record-breaking-extreme-forecasting]]: The prediction of meteorological events that exceed historical bounds, representing a primary challenge for machine learning models trained on historical data.

## Archivist Review

Approved concepts highlight the paradigm shift toward probabilistic AI architectures in weather prediction and the specific challenge of record-breaking events. The open questions address fundamental bottlenecks regarding out-of-distribution extrapolation in a changing climate and the generalization of these findings to more stochastic variables like precipitation. Rejected items include a legacy NWP system and a methodological critique that, while important, does not constitute a standalone ML concept.

### Approved Concepts
- Probabilistic AI Weather Prediction: The paper demonstrates that switching from deterministic to probabilistic AI weather models resolves the perceived performance gap in extreme events.
- Record-Breaking Extreme Forecasting: The paper specifically addresses 'record-breaking' events, which are traditionally thought to be the Achilles' heel of data-driven models.

### Approved Open Questions
- Extrapolation Limits for Unprecedented Extremes: Understanding the extrapolation limits of data-driven models is critical for climate adaptation and long-term safety.
- Generalization to Non-Thermal Extremes: Precipitation is harder to forecast and often exhibits higher spatial and temporal variability than temperature.

### Rejected Candidates
- [dataset] ECMWF IFS Ensemble (`ecmwf-ifs`) - duplicate_existing: This is a pre-existing numerical weather prediction system, not a new dataset or architectural contribution of this paper.
- [concept] Deterministic Verification Bias (`deterministic-verification-bias`) - not_novel: While a key finding, this is more of a methodological critique of existing evaluation practices than a new reusable machine learning concept or architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.20519)
- [PDF](https://arxiv.org/pdf/2610.20519)

