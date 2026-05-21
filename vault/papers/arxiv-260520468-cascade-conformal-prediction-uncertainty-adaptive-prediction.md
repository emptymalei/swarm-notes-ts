---
# CSL-compatible fields
title: "CASCADE Conformal Prediction: Uncertainty-Adaptive Prediction Intervals for Two-Stage Clinical Decision Support"
author:
  - literal: "Ricardo Diaz-Rincon"
  - literal: "Muxuan Liang"
  - literal: "Adolfo Ramirez-Zamora"
  - literal: "Benjamin Shickel"
issued:
  date-parts:
    - [2026, 5, 19]
url: "https://arxiv.org/abs/2605.20468"

# Custom fields
paper_id: "2605.20468"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "cascade-conformal-prediction"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-21T05:33:00Z"
created_at: "2026-05-21T05:33:00Z"
---

# CASCADE Conformal Prediction: Uncertainty-Adaptive Prediction Intervals for Two-Stage Clinical Decision Support

**Authors**: Ricardo Diaz-Rincon, Muxuan Liang, Adolfo Ramirez-Zamora, Benjamin Shickel
**Date**: 2026-05-19
**Paper ID**: [arxiv:2605.20468](https://arxiv.org/abs/2605.20468)

## Summary

CASCADE is a conformal prediction framework designed for two-stage clinical decision support, specifically addressing medication management in Parkinson's disease. The method propagates epistemic uncertainty from an initial medication-change classifier to dynamically scale the intervals of a secondary dose-forecasting regression model. By utilizing Venn-Abers multi-probabilistic uncertainty to inform non-conformity scores, the approach produces more efficient and adaptive intervals compared to traditional conformal methods. This allows for narrower, high-confidence predictions when appropriate, while ensuring robust coverage for cases with higher model uncertainty.

## Key Contributions

- Introduces CASCADE, a framework that dynamically scales regression intervals using epistemic uncertainty derived from a primary classification task.
- Demonstrates that mapping Venn-Abers multi-probabilistic uncertainty to non-conformity scores enables continuous risk adaptation in clinical decision support.
- Achieves 38.9% narrower prediction intervals for confident cases compared to standard conformal baselines while maintaining robust coverage.

## Key Concepts

- [[cascade-conformal-prediction]]: A conformal prediction framework that uses epistemic uncertainty from a classification model to dynamically adapt prediction intervals in a secondary regression task.

## Archivist Review

I have approved CASCADE as it represents a meaningful, reusable methodological advance in conformal prediction for multi-stage clinical pipelines, explicitly addressing uncertainty propagation. I rejected the subcomponent mapping as it is internal to the CASCADE framework's definition. No datasets or open questions were sufficiently novel or central to merit long-term storage in this instance.

### Approved Concepts
- CASCADE Conformal Prediction: Introduces a mechanism to propagate uncertainty between heterogeneous machine learning tasks (classification to regression), enabling task-dependent interval adaptation.

### Rejected Candidates
- [concept] Venn-Abers Mapping of Non-conformity Scores (`cascade-conformal-prediction-subcomponent-venn-abers-mapping`) - subcomponent_of_broader_mechanism: This is a specific implementation detail of the broader CASCADE mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.20468)
- [PDF](https://arxiv.org/pdf/2605.20468)

