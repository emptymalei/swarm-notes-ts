---
# CSL-compatible fields
title: "Forecasting the first Edge Localized Mode (ELM) after LH-transition with a neural network trained on Doppler Backscattering data from DIII-D"
author:
  - literal: "Nathan Qi Xuan Teo"
  - literal: "Kshitish Barada"
  - literal: "Valerian Hall-Chen"
  - literal: "Lin Gu"
  - literal: "Terry Lee Rhodes"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06508"

# Custom fields
paper_id: "2604.06508"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "survival-analysis-plasma-event-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:55:58Z"
created_at: "2026-04-09T04:55:58Z"
---

# Forecasting the first Edge Localized Mode (ELM) after LH-transition with a neural network trained on Doppler Backscattering data from DIII-D

**Authors**: Nathan Qi Xuan Teo, Kshitish Barada, Valerian Hall-Chen, Lin Gu, Terry Lee Rhodes
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06508](https://arxiv.org/abs/2604.06508)

## Summary

This paper introduces a neural network-based predictive tool for forecasting the first Edge Localized Mode (ELM) crash following an LH-transition in fusion plasmas. By adapting the DeepHit architecture to utilize Doppler Backscattering (DBS) diagnostic data from the DIII-D tokamak, the model achieves the ability to forecast ELM events 100 ms before they occur. The study provides a foundational framework for developing active ELM-mitigation strategies to protect plasma-facing components.

## Key Contributions

- Proposes a neural network architecture adapted from DeepHit to forecast the first Edge Localized Mode (ELM) after an LH-transition.
- Achieves reliable forecasting of ELM crashes 100 ms prior to occurrence using 50 ms of Doppler Backscattering (DBS) spectrogram data as input.
- Establishes a proof-of-concept for real-time ELM mitigation triggering in the DIII-D tokamak device.

## Open Questions & Future Work

- [[fusion-forecasting-generalization-bottleneck]]

## Key Concepts

- [[survival-analysis-plasma-event-forecasting]]: The use of survival analysis neural network architectures to predict the time-to-event probability for critical plasma instabilities like Edge Localized Modes.

## Archivist Review

I approved a general concept for survival analysis in plasma forecasting to capture the methodological shift from point-forecasting to time-to-event estimation. I also approved a refined version of the open question regarding generalization bottlenecks in fusion plasma forecasting, as this is a fundamental barrier to real-world deployment in the field. DIII-D was rejected as a dataset because it is an individual experiment device/facility rather than a benchmarked, structured dataset ready for general research use.

### Approved Concepts
- Survival Analysis for Plasma Instability Forecasting: Applying survival analysis architectures like DeepHit to temporal event forecasting in fusion plasmas is a significant departure from standard point-forecasting, offering a framework for predicting time-to-critical-event in high-stakes physical systems.

### Approved Open Questions
- Fusion Forecasting Generalization Bottlenecks: Generalization is the central bottleneck for deploying ML-based safety and control systems in fusion devices, where labeled data for critical failure modes is inherently sparse.

### Rejected Candidates
- [concept] DeepHit-based ELM Forecasting (`deephit-based-elm-forecasting`) - other: Renamed to a more general concept ('Survival Analysis for Plasma Instability Forecasting') to better capture the underlying methodology rather than the specific application.
- [open_question] Improving Model Generalization for Tokamaks (`improving-model-robustness-and-generalization-in-tokamak-forecasting`) - other: Rewritten as a cleaner, more generalized research question in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.06508)
- [PDF](https://arxiv.org/pdf/2604.06508)

