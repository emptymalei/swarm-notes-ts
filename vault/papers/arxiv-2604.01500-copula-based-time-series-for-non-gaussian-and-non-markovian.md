---
# CSL-compatible fields
title: "Copula-Based Time Series for Non-Gaussian and Non-Markovian Stationary Processes"
author:
  - literal: "Sven Pappert"
  - literal: "Harry Joe"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01500"

# Custom fields
paper_id: "2604.01500"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:20:31Z"
created_at: "2026-04-03T05:20:31Z"
---

# Copula-Based Time Series for Non-Gaussian and Non-Markovian Stationary Processes

**Authors**: Sven Pappert, Harry Joe
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01500](https://arxiv.org/abs/2604.01500)

## Summary

This paper introduces a generalized copula-based approach for modeling stationary, univariate time series that captures non-Gaussian and non-Markovian temporal dependencies. By combining Markov sequences of order p with q-dependent processes, the framework provides a flexible alternative to traditional linear models. The authors derive essential distributional properties, establish links to standard Gaussian-ARMA and GARCH models, and develop robust maximum likelihood estimation methods. Empirical evaluation on US inflation and German wind energy data highlights the model's effectiveness in complex, non-linear probabilistic forecasting tasks.

## Key Contributions

- Proposes a generalized copula-based framework for stationary time series, extending Markov sequences of order p and q-dependent processes.
- Provides theoretical connections between the proposed model class and classical Gaussian-ARMA and Gaussian-GARCH(1,1) models.
- Develops maximum likelihood estimation procedures and analyzes the properties of the copula moving aggregate (MAG(1)) process.
- Demonstrates superior probabilistic forecasting performance on real-world datasets including US inflation and German wind energy production.

## Open Questions & Future Work

- [[copula-ts-consistency-conditions]]
- [[copula-arma-generalization-limits]]

## Archivist Review

I have approved the two open questions as they address fundamental theoretical limits of the copula-based time series modeling framework relative to classical linear models. I have not approved any concepts as the paper describes specific model constructions (e.g., specific Markov/Moving Aggregate combinations) that do not constitute broad or recurring methodological primitives outside the scope of this specific family of copula approaches. The paper's core methodology is a specialized refinement of existing copula theory rather than a new standalone paradigm.

### Approved Open Questions
- Consistency conditions for copula-based time series: This is a fundamental theoretical gap that prevents practitioners from verifying if their chosen model architecture and copula selection satisfy the requirements for consistent estimation in practice.
- Limits of copula-based ARMA generalization: Resolving this would determine the limits of the copula-based approach in replicating the flexibility of classical linear models and would clarify if the current model structures are truly sufficient or if more advanced constructions are required.

## Links

- [Abstract](https://arxiv.org/abs/2604.01500)
- [PDF](https://arxiv.org/pdf/2604.01500)

