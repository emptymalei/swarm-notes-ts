---
# CSL-compatible fields
title: "Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models"
author:
  - literal: "Nikeethan Selvaratnam"
  - literal: "Dorinel Bastide"
  - literal: "Clément Fernandes"
  - literal: "Wojciech Pieczynski"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21734"

# Custom fields
paper_id: "2604.21734"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "multivariate-hmm-auxiliary-covariates"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:04Z"
created_at: "2026-04-25T04:54:04Z"
---

# Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models

**Authors**: Nikeethan Selvaratnam, Dorinel Bastide, Clément Fernandes, Wojciech Pieczynski
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21734](https://arxiv.org/abs/2604.21734)

## Summary

This paper addresses the challenge of modeling operational risk losses by proposing an extension to multivariate Hidden Markov Models. The model incorporates a dedicated auxiliary variable to capture the dependency between risk losses and macroeconomic covariates, providing a more robust framework for stress testing. Calibration is performed using the Expectation-Maximization (EM) algorithm, with evaluation demonstrating the relevance of these covariates across different risk-event types.

## Key Contributions

- Proposes a multivariate Hidden Markov Model (HMM) extension to model the relationship between macroeconomic covariates and heterogeneous operational risk losses.
- Details the EM-based calibration process for handling auxiliary variables in the context of risk-event data.
- Demonstrates the effectiveness of including macroeconomic covariates for improving the predictive modeling of risk-event types.

## Open Questions & Future Work

- [[heavy-tailed-hmm-operational-risk]]

## Key Concepts

- [[multivariate-hmm-auxiliary-covariates]]: An extension of Hidden Markov Models that incorporates auxiliary macroeconomic variables to improve prediction of heterogeneous operational risk losses.

## Archivist Review

The paper introduces a structured approach to integrating exogenous covariates into HMMs, which is a valuable technique in time-series modeling. The concept is approved for its reusability across different domains requiring state-space modeling with external inputs. The open question regarding the Gaussian limitation of standard HMMs is a well-defined research bottleneck that deserves tracking.

### Approved Concepts
- Multivariate Hidden Markov Models with Auxiliary Covariates: Enables direct integration of exogenous macroeconomic signals into state-space modeling for operational risk.

### Approved Open Questions
- HMMs for Heavy-Tailed Distributions: The Gaussian assumption is known to be inadequate for modeling the extreme-value behavior characteristic of financial operational losses; adapting these models to heavy-tailed distributions is critical for more accurate risk estimation.

## Links

- [Abstract](https://arxiv.org/abs/2604.21734)
- [PDF](https://arxiv.org/pdf/2604.21734)

