---
# CSL-compatible fields
title: "Conflict Forecasting via Conformal Prediction for Markov Processes"
author:
  - literal: "Aditya Basarkar"
  - literal: "Emmett B. Kendall"
  - literal: "David Randahl"
  - literal: "Jonathan P. Williams"
  - literal: "Gudmund H. Hermansen"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25139"

# Custom fields
paper_id: "2604.25139"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "uncertainty-quantification"
  - "causal-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "conformal-prediction-for-markov-processes"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:47Z"
created_at: "2026-04-29T05:11:47Z"
---

# Conflict Forecasting via Conformal Prediction for Markov Processes

**Authors**: Aditya Basarkar, Emmett B. Kendall, David Randahl, Jonathan P. Williams, Gudmund H. Hermansen
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25139](https://arxiv.org/abs/2604.25139)

## Summary

This paper addresses the challenge of conflict forecasting by applying conformal prediction to temporally-dependent Markovian data. By replacing standard point-prediction with uncertainty-aware prediction sets, the proposed method provides valid confidence intervals that are robust to model misspecification. The authors specifically evaluate the approach against likelihood-based strategies and discuss the inherent difficulties of applying conformal inference when the exchangeability assumption is violated. The findings demonstrate effective application of this framework to real-world conflict dynamics across diverse geopolitical contexts.

## Key Contributions

- Introduces a framework for applying conformal prediction to discrete-state Markov processes for conflict forecasting.
- Demonstrates that conformal prediction provides robust uncertainty quantification compared to likelihood-based strategies under model misspecification.
- Provides empirical validation through real-world forecasts of conflict dynamics across multiple countries.

## Open Questions & Future Work

- [[conformal-prediction-validity-for-markovian-data]]

## Key Concepts

- [[conformal-prediction-for-markov-processes]]: A framework for generating valid prediction sets for future state-sequences of a Markov process using conformal prediction.

## Archivist Review

I approved the 'Conformal Prediction for Markov Processes' framework as it represents a specialized adaptation of conformal inference for non-exchangeable time-series data. I also added an open question regarding the theoretical validity conditions for such approaches, as the paper explicitly identifies the violation of exchangeability as a critical limitation. No datasets were approved as none were specifically named or centralized in the provided text.

### Approved Concepts
- Conformal Prediction for Markov Processes: Extends conformal prediction to non-exchangeable Markovian temporal data, providing a framework for valid uncertainty quantification under model misspecification.

### Approved Open Questions
- Conformal Validity for Markovian Data: Validating the application of conformal inference to dependent data is essential for reliable uncertainty quantification in high-stakes time-series forecasting.

### Rejected Candidates
- [concept] Conformal Prediction for Markov Processes (`conformal-prediction-for-markov-processes`) - other: This concept is being approved; the summary note below clarifies the selection criteria.

## Links

- [Abstract](https://arxiv.org/abs/2604.25139)
- [PDF](https://arxiv.org/pdf/2604.25139)

