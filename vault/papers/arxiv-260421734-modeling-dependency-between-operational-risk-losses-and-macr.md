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
  - "time-series"
  - "risk-modeling"
  - "hidden-markov-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multivariate-hmm-auxiliary-covariates"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:07:17Z"
created_at: "2026-04-24T05:07:17Z"
---

# Modeling dependency between operational risk losses and macroeconomic variables using Hidden Markov Models

**Authors**: Nikeethan Selvaratnam, Dorinel Bastide, Clément Fernandes, Wojciech Pieczynski
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21734](https://arxiv.org/abs/2604.21734)

## Summary

This paper introduces an extended multivariate Hidden Markov Model to capture the complex, regime-dependent dynamics between operational risk losses and macroeconomic variables. By incorporating a dedicated auxiliary variable for economic covariates, the model improves the representation of heterogeneous loss patterns common in financial risk scenarios. The framework is calibrated using an Expectation-Maximization algorithm and validated across multiple risk-event types, highlighting the effectiveness of macroeconomic integration for stress testing and predictive modeling.

## Key Contributions

- Proposes an extended multivariate Hidden Markov Model (HMM) architecture that explicitly incorporates macroeconomic covariates via a third auxiliary variable to model operational risk dependencies.
- Develops an expectation-maximization (EM) calibration framework tailored for the unique statistical properties of operational risk loss data.
- Demonstrates the relevance of macroeconomic covariates in capturing heterogeneous regime-switching dynamics across diverse risk-event types.

## Open Questions & Future Work

- [[heavy-tailed-hmm-operational-risk]]

## Key Concepts

- [[multivariate-hmm-auxiliary-covariates]]: An extension of Hidden Markov Models that utilizes a third auxiliary variable to integrate exogenous covariates into regime-switching dynamics.

## Archivist Review

The paper proposes a specialized HMM extension for integrating macroeconomic variables into risk modeling. I approved the core conceptual contribution regarding the auxiliary covariate variable and the open question regarding the necessity of handling heavy-tailed loss distributions, as both address fundamental limitations in financial risk modeling. No datasets were approved as none were explicitly named or uniquely central to the methodology.

### Approved Concepts
- Multivariate Hidden Markov Model with Auxiliary Covariates: Provides a specific architectural approach to modeling regime-dependent dependencies between target variables and exogenous covariates in HMMs.

### Approved Open Questions
- Heavy-tailed distributions for HMMs: Standard HMM formulations frequently underestimate the frequency and magnitude of extreme risks, which is a critical limitation for applications in finance and operational risk.

## Links

- [Abstract](https://arxiv.org/abs/2604.21734)
- [PDF](https://arxiv.org/pdf/2604.21734)

