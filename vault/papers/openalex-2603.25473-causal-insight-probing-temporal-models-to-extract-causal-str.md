---
# CSL-compatible fields
title: "Causal-INSIGHT: Probing Temporal Models to Extract Causal Structure"
author:
  - literal: "Benjamin Redden"
  - literal: "Hui Wang"
  - literal: "Shuyan Li"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25473"

# Custom fields
paper_id: "2603.25473"
paper_source: "openalex"
domain: "time-series"
tags:
  - "causality"
  - "time-series-analysis"
  - "interpretability"
  - "model-agnostic"
architectures:
  []
datasets:
  []
concept_slugs:
  - "causal-insight"
  - "qbic-sparsity-aware-selection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:18:01Z"
created_at: "2026-03-29T20:18:01Z"
---

# Causal-INSIGHT: Probing Temporal Models to Extract Causal Structure

**Authors**: Benjamin Redden, Hui Wang, Shuyan Li
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25473](https://arxiv.org/abs/2603.25473)

## Summary

This paper introduces Causal-INSIGHT, a model-agnostic, post-hoc framework designed to extract model-implied, directed, time-lagged causal structures from trained temporal predictors. The methodology relies on applying systematic, intervention-inspired input clamping during inference time to observe the resulting changes in the predictor's output, thereby mapping its internal dependencies. To select the final, parsimonious structure from the observed influence signals, the authors introduce Qbic, a sparsity-aware graph selection criterion that optimizes the trade-off between predictive fidelity and structural complexity. Experiments across synthetic and realistic benchmarks demonstrate the framework's generality across architectures, competitive structural accuracy, and superior temporal delay localization.

## Key Contributions

- Introduction of Causal-INSIGHT, a model-agnostic, post-hoc interpretation framework that extracts directed, time-lagged influence structure via intervention-inspired input clamping on pre-trained temporal models.
- Development of Qbic, a novel sparsity-aware graph selection criterion that balances predictive fidelity and structural complexity for identifying the final causal graph without requiring ground-truth labels.
- Demonstration that Causal-INSIGHT generalizes across diverse backbone architectures and maintains competitive structural accuracy in causal extraction.
- Achieving significant improvements in temporal delay localization when Causal-INSIGHT is applied to existing temporal predictors.

## Limitations

The extracted structure is model-implied and predictor-dependent, reflecting the dependencies the model relies on rather than the true data-generating process.

## Open Questions & Future Work

- [[adaptive-clamping-schemes]]
- [[multi-horizon-predictor-probing]]

## Key Concepts

- [[causal-insight]]: A model-agnostic, post-hoc interpretation framework for extracting model-implied, directed, time-lagged influence structure from trained temporal predictors using intervention-inspired input clamping.
- [[qbic-sparsity-aware-selection]]: A sparsity-aware graph selection criterion designed to balance the fidelity of extracted causal structures against their complexity, useful when ground-truth labels are unavailable.

## Archivist Review

The core contributions, Causal-INSIGHT (the framework) and Qbic (the selection criterion), were approved as they represent reusable, novel methodologies in time series interpretability. Two substantial open questions regarding the generalization of the probing technique to multi-horizon predictors and the development of more sophisticated adaptive clamping schemes were also approved as they represent key future research directions for this methodology. All other concepts were rejected as they were either too generic or implementation details of the main framework.

### Approved Concepts
- Causal-INSIGHT: It is the primary proposed framework for extracting causal structure from temporal models based on intervention-inspired clamping.
- Qbic (Sparsity-Aware Graph Selection): Qbic is the novel criterion used by Causal-INSIGHT to select the final, parsimonious causal structure from the influence signals.

### Approved Open Questions
- Develop adaptive input clamping schemes: Current clamping is extremal and fixed in time ($t_0=0$), which may not be optimal for all time series characteristics or all learned temporal dependencies, especially if important influences are more subtle or occur at later offsets.
- Extend probing to multi-horizon predictors: Multi-horizon predictors are common in time series modeling, and adapting post-hoc probing techniques to them is essential for broader interpretability in forecasting tasks.

### Rejected Candidates
- [concept] Model-implied causal structure extraction (`causal-structure-extraction`) - subcomponent_of_broader_mechanism: This is too generic; the specific reusable contribution is Causal-INSIGHT.
- [concept] Intervention-inspired input clamping (`intervention-inspired-input-clamping`) - subcomponent_of_broader_mechanism: This technique is described as the mechanism *within* Causal-INSIGHT and is not significant enough for a standalone concept compared to the framework itself.

## Links

- [Abstract](https://arxiv.org/abs/2603.25473)
- [PDF](https://arxiv.org/pdf/2603.25473)

