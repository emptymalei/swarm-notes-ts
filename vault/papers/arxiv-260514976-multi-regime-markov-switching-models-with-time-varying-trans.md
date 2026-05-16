---
# CSL-compatible fields
title: "Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields"
author:
  - literal: "Samuel Modée"
  - literal: "Yushu Li"
  - literal: "Sjur Westgaard"
  - literal: "Stein Andreas Bethuelsen"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14976"

# Custom fields
paper_id: "2605.14976"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "econometrics"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:22Z"
created_at: "2026-05-16T05:11:22Z"
---

# Multi-regime Markov-switching models with time-varying transition probabilities: An application to U.S. Treasury yields

**Authors**: Samuel Modée, Yushu Li, Sjur Westgaard, Stein Andreas Bethuelsen
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14976](https://arxiv.org/abs/2605.14976)

## Summary

This paper extends K-regime Markov-switching models with time-varying transition probabilities (TVTP), specifically generalizing the GAS-based two-regime model. Through comprehensive Monte Carlo simulations, the authors identify critical non-identifiability issues regarding the GAS score coefficient. Applying the framework to U.S. Treasury yield data, they observe that exogenous variable specifications often outperform endogenous GAS models, which face convergence challenges in this regime-switching context.

## Key Contributions

- Extends the Generalized Autoregressive Score (GAS) Markov-switching framework to the general K-regime case with regime-specific means and variances.
- Demonstrates through simulation that while regime-level parameters are recoverable, the GAS score coefficient suffers from non-identifiability.
- Shows that one-step forecasts are robust to TVTP misspecification, whereas filtered regime probability estimation is highly sensitive to model specification.

## Open Questions & Future Work

- [[identifiability-of-gas-score-coefficients]]
- [[sensitivity-to-tvtp-link-functions]]

## Archivist Review

The paper presents a specialized study on the identifiability of GAS-driven TVTP models. The concepts proposed were largely software-specific or incremental extensions of existing econometrics literature. The open questions regarding identifiability and link function sensitivity were approved as they address significant, recurring obstacles in the estimation of dynamic regime-switching models.

### Approved Open Questions
- Identifiability of GAS score coefficients: This issue limits the practical application of score-driven TVTP models, as standard maximum likelihood estimation fails to reliably recover the intended dynamic parameters.
- Sensitivity to TVTP link functions: Different link functions could potentially mitigate identifiability issues or improve the flexibility of the regime-transition dynamics.

### Rejected Candidates
- [concept] multiregimeTVTP (`multiregimetvtp`) - not_reusable: Software package names are generally not suitable as conceptual vault notes unless they introduce a fundamentally novel methodology.

## Links

- [Abstract](https://arxiv.org/abs/2605.14976)
- [PDF](https://arxiv.org/pdf/2605.14976)

