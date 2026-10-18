---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "What Does History Add? Calendar Controls and Information-Timing Audits for University Trajectory Forecasting"
description: "This paper conducts an 'information-timing audit' to determine whether historical data summaries actually improve university trajectory forecasting when compared to simple temporal baselines. Using Ridge regression models and a rule-based simulator, the author introduces 'calendar controls'—models that only know the length of history—to isolate the true marginal utility of historical content. The findings suggest that while history improves NRMSE over current-state models, much of this improvement is attributable to the history length itself (the calendar effect), with historical content providing negligible additional benefit for specific variables like fatigue."
resource: "https://arxiv.org/abs/2610.21419"
tags:
  - "trajectory-prediction"
  - "forecasting"
  - "evaluation-framework"
  - "time-series-analysis"
  - "statistical-validation"
  - "simulation"
  - "ridge-regression"
  - "university-trajectories"
timestamp: "2026-10-18T00:21:05Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Zepei Cao"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21419"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "calendar-control"
    description: "A baseline methodology that uses the duration of historical observation as a predictor to isolate the actual information value of historical data content."
  - name: "information-timing-audit"
    description: "A systematic evaluation framework designed to quantify the marginal utility of historical summaries versus simple temporal baselines."
datasets:
  []
open_questions:
  - name: "constraint-satisfaction-trajectory-forecasting"
    description: "How can forecasting models be regularized or constrained to ensure that derived features remain within the physical or logical support of the underlying system during multi-step prediction, especially when the simulator's support is known but the model relies on historical summaries?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:21:05Z"
created_at: "2026-10-18T00:21:05Z"
---

# What Does History Add? Calendar Controls and Information-Timing Audits for University Trajectory Forecasting

**Authors**: Zepei Cao
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21419](https://arxiv.org/abs/2610.21419)

## Summary

This paper conducts an 'information-timing audit' to determine whether historical data summaries actually improve university trajectory forecasting when compared to simple temporal baselines. Using Ridge regression models and a rule-based simulator, the author introduces 'calendar controls'—models that only know the length of history—to isolate the true marginal utility of historical content. The findings suggest that while history improves NRMSE over current-state models, much of this improvement is attributable to the history length itself (the calendar effect), with historical content providing negligible additional benefit for specific variables like fatigue.

## Key Contributions

- Introduces the 'calendar control' methodology to differentiate between the predictive value of historical event content versus the mere duration of the observation period.
- Demonstrates through an 804,000-record audit that apparent gains from six-month historical summaries are often statistically insignificant when compared to length-only controls in university trajectory simulators.
- Provides an exploratory decomposition of feature performance, revealing that while 'preparation index' and 'funds' benefit from history, 'fatigue' predictions frequently violate simulator constraints.
- Establishes a rigorous evaluation protocol for simulator-based trajectory forecasting, including family-held-out evaluations and matched recursive references.

## Limitations

The study is an evaluation of a rule-based simulator and does not assess real-world student behavior, causal effects of actions, or the memory capabilities of modern large language models.

## Open Questions & Future Work

- [[constraint-satisfaction-trajectory-forecasting]]

## Key Concepts

- [[calendar-control]]: A baseline methodology that uses the duration of historical observation as a predictor to isolate the actual information value of historical data content.
- [[information-timing-audit]]: A systematic evaluation framework designed to quantify the marginal utility of historical summaries versus simple temporal baselines.

## Archivist Review

The approved concepts 'Calendar Control' and 'Information-Timing Audit' provide a valuable methodological framework for evaluating model memory and the utility of historical data in time-series forecasting. They address a frequent pitfall in the field where temporal duration is confounded with historical information. The open question on constraint satisfaction is approved as it highlights a specific, measurable failure mode in trajectory forecasting where model predictions drift outside of valid system support.

### Approved Concepts
- Calendar Control: It addresses a common confounding factor in time-series forecasting where the duration of an entity's observation period (e.g., student seniority or patient time-in-system) provides more predictive signal than the actual content of the historical sequence.
- Information-Timing Audit: Provides a structured framework to decompose model performance into contributions from the current state, historical state, and temporal metadata, preventing the misattribution of performance gains to model memory.

### Approved Open Questions
- Constraint Satisfaction in Trajectory Forecasting: Ensuring predictions remain within logical bounds is critical for the reliability and safety of simulators used in decision-support systems, as out-of-bounds features can lead to nonsensical downstream simulations.

## Links

- [Abstract](https://arxiv.org/abs/2610.21419)
- [PDF](https://arxiv.org/pdf/2610.21419)

