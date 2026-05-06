---
# CSL-compatible fields
title: "Partial Effective Information Decomposition for Synergistic Causality"
author:
  - literal: "Mingzhe Yang"
  - literal: "Shuo Wang"
  - literal: "Jiang Zhang"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03267"

# Custom fields
paper_id: "2605.03267"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "KnowAir-V2"
concept_slugs:
  - "partial-effective-information-decomposition-peid"
dataset_slugs:
  - "knowair-v2"
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:53Z"
created_at: "2026-05-06T05:12:53Z"
---

# Partial Effective Information Decomposition for Synergistic Causality

**Authors**: Mingzhe Yang, Shuo Wang, Jiang Zhang
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03267](https://arxiv.org/abs/2605.03267)

## Summary

This paper introduces Partial Effective Information Decomposition (PEID), a new framework for analyzing multivariate causal relations in complex systems. By leveraging maximum-entropy interventions to eliminate redundancy among input variables, PEID effectively decomposes source variable influences into unique and synergistic components. The framework enables the construction of causal graphs with hyperedges and downward causation, and its utility is validated by extracting interpretable causal structures from air quality forecasting models.

## Key Contributions

- Introduces Partial Effective Information Decomposition (PEID) to quantify synergistic causal relations using maximum-entropy interventions.
- Demonstrates that PEID allows for the definition of causal graphs incorporating hyperedges and downward causation.
- Evaluates PEID on the KnowAir-V2 dataset, showing it can successfully extract interpretable inter-station causal structures from learned dynamical models.

## Open Questions & Future Work

- [[peid-non-markovian-target-decomposition-limitations]]

## Key Concepts

- [[partial-effective-information-decomposition-peid]]: An interventionist information-theoretic framework that decomposes source variable influences on a target into unique and synergistic components under maximum-entropy interventions.

## Archivist Review

The submission presents a novel information-theoretic framework (PEID) for decomposing causal influences. I have approved PEID as a distinct contribution to causal inference and included the KnowAir-V2 dataset, which serves as its primary empirical validation in the context of dynamical modeling. The open question was refined to capture the theoretical bottleneck of non-Markovian extensions and target-side decomposition, which is vital for the framework's broader utility in complex time-series analysis.

### Approved Concepts
- Partial Effective Information Decomposition (PEID): Provides a novel, unified, and computable information-theoretic framework for decomposing multivariate synergistic causal relations through interventionist causation.

### Approved Open Questions
- PEID non-Markovian and target-side limitations: These limitations currently restrict the framework from capturing causal structures in high-dimensional real-world systems with latent memory effects.

## Datasets

- [[knowair-v2]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03267)
- [PDF](https://arxiv.org/pdf/2605.03267)

