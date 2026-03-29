---
# CSL-compatible fields
title: "Interpretable PM2.5 Forecasting for Urban Air Quality: A Comparative Study of Operational Time-Series Models"
author:
  - literal: "Moazzam Umer Gondal"
  - literal: "Hamad ul Qudous"
  - literal: "Asma Ahmad Farhan"
  - literal: "Sultan Alamri"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25495"

# Custom fields
paper_id: "2603.25495"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "interpretability"
  - "model-series-modeling"
  - "model-series-evaluation"
  - "deployment"
architectures:
  []
datasets:
  []
concept_slugs:
  - "online-residual-correction"
  - "leakage-aware-forecasting-workflow"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:15:22Z"
created_at: "2026-03-29T20:15:22Z"
---

# Interpretable PM2.5 Forecasting for Urban Air Quality: A Comparative Study of Operational Time-Series Models

**Authors**: Moazzam Umer Gondal, Hamad ul Qudous, Asma Ahmad Farhan, Sultan Alamri
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25495](https://arxiv.org/abs/2603.25495)

## Summary

This paper compares the performance and efficiency of lightweight, interpretable time-series models (SARIMAX, Facebook Prophet, NeuralProphet) for hourly PM2.5 forecasting in Beijing, employing a leakage-aware workflow. The models were tested under walk-forward refitting and frozen deployment with online residual correction. Results indicate Facebook Prophet leads in walk-forward accuracy, but corrected SARIMAX achieves the best overall error (MAE 32.50) in the frozen regime, which offers significant computational savings. The findings support using interpretable additive strategies balanced with deployment optimization techniques like residual correction for practical air quality management.

## Key Contributions

- Demonstrated that lightweight additive models (SARIMAX, Prophet) can achieve competitive accuracy against potentially more complex models for hourly PM2.5 forecasting in an urban setting.
- Evaluated two critical deployment regimes: weekly walk-forward refitting and frozen forecasting with online residual correction, showing the latter offers significant runtime savings.
- Identified that corrected SARIMAX yielded the lowest error (MAE 32.50) under the frozen-model regime via online residual correction, while Facebook Prophet was superior in the walk-forward regime.
- Showcased that online residual correction substantially improves deployment efficiency, reducing Facebook Prophet runtime from ~15 minutes to under 47 seconds while maintaining accuracy close to the fully retrained version.

## Limitations

The study focused only on hourly PM2.5 prediction in Beijing, and the generalizability of the findings to other pollutants or regions is not established. The relative performance of NeuralProphet was consistently poor, suggesting its hyperparameter sensitivity or architecture may not suit this specific forecasting task.

## Open Questions & Future Work

- [[lightweight-adaptation-transferability]]
- [[lightweight-model-abrupt-regime-shifts]]

## Key Concepts

- [[online-residual-correction]]: A deployment strategy for time-series forecasting where a pre-trained model's predictions are adjusted online using the difference between the actual observed values and the model's previous predictions.
- [[leakage-aware-forecasting-workflow]]: A structured workflow for preparing time-series data that explicitly accounts for and prevents information leakage between training and testing sets, often involving strict chronological partitioning.

## Archivist Review

Two specific methodological concepts were approved: 'Online Residual Correction' as a reusable deployment strategy, and the 'Leakage-Aware Forecasting Workflow' due to its critical role in ensuring sound time-series evaluation. Two open questions focusing on transferability and robustness to regime shifts were selected as they represent substantial, domain-relevant challenges for operationalizing lightweight models. Other candidates were rejected for being standard forecasting terminology (Perfect Prognosis, Walk-forward Refitting) or for being too generic in their scope as future work.

### Approved Concepts
- Online Residual Correction: It is a specific technique used to adapt frozen models in deployment, potentially reducing computational overhead while maintaining accuracy, which is a key practical consideration.
- Leakage-Aware Forecasting Workflow: It details a specific, careful methodology for time-series preparation to avoid data leakage, which is crucial for robust forecasting evaluation.

### Approved Open Questions
- Extend lightweight model adaptation: Assessing transferability is crucial for operationalizing lightweight forecasting models beyond the single city (Beijing) studied, ensuring robustness across diverse urban environments.
- Lightweight model robustness to shifts: Understanding robustness to rare, high-impact events like abrupt regime shifts is vital for emergency planning and public safety applications of air quality forecasting.

### Rejected Candidates
- [concept] Perfect Prognosis setting (`perfect-prognosis-setting`) - not_novel: This is a standard operational setting in forecasting, not a novel technical contribution of this paper.
- [concept] Walk-forward Refitting (`walk-forward-refitting`) - not_novel: This is a standard, well-known model update strategy in time-series evaluation, not a novel concept introduced by the paper.
- [concept] Frozen Forecasting (`frozen-forecasting`) - not_novel: This is a standard deployment scenario where a model's weights are fixed, not a novel mechanism. The novelty lies in the residual correction applied to it.
- [open_question] Integrate lightweight hybrid techniques (`lightweight-hybrid-model-integration`) - low_impact: This is a reasonable extension of the current work but lacks the specificity of an explicit, unresolved bottleneck identified by the authors; it's more general future work boilerplate.
- [open_question] Explore federated learning schemes (`federated-learning-for-generalization`) - low_impact: This is a standard, generic future work suggestion related to privacy and generalization that is not intrinsically tied to the core comparative findings of the lightweight models.

## Links

- [Abstract](https://arxiv.org/abs/2603.25495)
- [PDF](https://arxiv.org/pdf/2603.25495)

