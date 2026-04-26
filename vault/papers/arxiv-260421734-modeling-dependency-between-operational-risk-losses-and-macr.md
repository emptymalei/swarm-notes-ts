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
processed_at: "2026-04-26T05:08:25Z"
created_at: "2026-04-26T05:08:25Z"
---

# Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models

**Authors**: Nikeethan Selvaratnam, Dorinel Bastide, Clément Fernandes, Wojciech Pieczynski
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21734](https://arxiv.org/abs/2604.21734)

## Summary

This paper addresses the challenge of modeling heterogeneous and time-dependent operational risk losses by proposing a novel extension of Hidden Markov Models. By introducing a third auxiliary variable, the model explicitly incorporates macroeconomic covariates to better capture the relationship between economic drivers and risk events. The authors detail the model calibration process using the Expectation-Maximization algorithm and provide empirical validation across different risk-event types.

## Key Contributions

- Introduces a multivariate Hidden Markov Model (HMM) framework that integrates macroeconomic covariates through a dedicated auxiliary latent variable to model operational risk losses.
- Develops a parameter estimation procedure for the proposed model using the Expectation-Maximization (EM) algorithm.
- Demonstrates the effectiveness of incorporating macroeconomic covariates for various operational risk-event types through empirical calibration analysis.

## Open Questions & Future Work

- [[heavy-tailed-hmm-operational-risk]]

## Key Concepts

- [[multivariate-hmm-auxiliary-covariates]]: A hidden Markov model extension that integrates macroeconomic covariates into multivariate time-series via a dedicated auxiliary variable.

## Archivist Review

The paper presents a clear extension of HMMs to include auxiliary covariates, which is a reusable methodology. I approved the concept and the question regarding heavy-tailed distributions, as tail risk is a fundamental challenge in financial risk modeling. The question on covariate selection was rejected as it pertains to general feature engineering rather than a specific scientific bottleneck.

### Approved Concepts
- Multivariate-HMM Auxiliary Covariates: The core novelty is the specific extension of HMMs to integrate external macroeconomic covariates via a latent auxiliary structure for operational risk modeling.

### Approved Open Questions
- Heavy-tailed HMMs for Operational Risk: Operational losses are notoriously heavy-tailed; using inappropriate Gaussian assumptions may lead to a systematic underestimation of extreme risks, which is critical for banking stability and regulatory capital requirements.

### Rejected Candidates
- [open_question] Covariate Selection for Operational Risk (`macroeconomic-covariate-selection-operational-risk`) - generic: This is a standard model selection and feature engineering task rather than a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.21734)
- [PDF](https://arxiv.org/pdf/2604.21734)

