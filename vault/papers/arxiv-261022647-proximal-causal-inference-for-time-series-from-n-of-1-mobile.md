---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Proximal Causal Inference for Time Series from N-of-1 Mobile Device Data"
description: "This paper addresses the problem of unmeasured confounding in intensive longitudinal studies, such as those involving mobile health (mHealth) data. It extends the Proximal Causal Inference (PCI) framework to a time series context, allowing for the identification of treatment effects by using past and future observations as proxies for hidden variables. The authors provide the necessary identifiability conditions, develop a bridge function for estimation, and establish asymptotic results, while demonstrating effectiveness through simulations and a case study on bipolar disorder patients."
resource: "https://arxiv.org/abs/2610.22647"
tags:
  - "time-series"
  - "causal-inference"
  - "longitudinal-data"
  - "longitudinal-analysis"
  - "statistical-inference"
  - "asymptotic-analysis"
  - "clinical-data"
  - "healthcare-ai"
timestamp: "2026-10-19T04:40:26Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Fanyu Cui"
  - literal: "Charlotte Fowler"
  - literal: "Xiaoxuan Cai"
  - literal: "Jukka-Pekka Onnela"
  - literal: "Justin Baker"
  - literal: "Linda Valeri"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22647"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "proximal-causal-inference-time-series"
    description: "An extension of the proximal causal inference framework to time series data that leverages past and future observations as natural proxies for unmeasured confounders."
datasets:
  []
open_questions:
  - name: "doubly-robust-proximal-time-series"
    description: "Existing proximal estimators for time series typically rely on the correct specification of a single outcome confounding bridge function. Developing doubly robust estimators that incorporate both outcome and treatment confounding bridge functions is an unresolved challenge. Such estimators would provide a safeguard by remaining unbiased as long as at least one of the bridge function models is correctly specified."
  - name: "non-stationary-proximal-causal-inference"
    description: "The extension of proximal causal inference to handle non-stationary time series or data with rapidly evolving treatment effects remains an open problem. Current methodologies often rely on stationarity or piecewise stable effect assumptions, which may not hold in real-world mobile health applications where patient states and environmental factors change continuously."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:40:26Z"
created_at: "2026-10-19T04:40:26Z"
---

# Proximal Causal Inference for Time Series from N-of-1 Mobile Device Data

**Authors**: Fanyu Cui, Charlotte Fowler, Xiaoxuan Cai, Jukka-Pekka Onnela, Justin Baker, Linda Valeri
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22647](https://arxiv.org/abs/2610.22647)

## Summary

This paper addresses the problem of unmeasured confounding in intensive longitudinal studies, such as those involving mobile health (mHealth) data. It extends the Proximal Causal Inference (PCI) framework to a time series context, allowing for the identification of treatment effects by using past and future observations as proxies for hidden variables. The authors provide the necessary identifiability conditions, develop a bridge function for estimation, and establish asymptotic results, while demonstrating effectiveness through simulations and a case study on bipolar disorder patients.

## Key Contributions

- Extended the Proximal Causal Inference (PCI) framework to time series settings, enabling the estimation of contemporaneous and lagged effects of time-varying treatments.
- Established new identifiability conditions that utilize past and future observations within an intensive longitudinal dataset as proxies for unmeasured confounders.
- Developed a bridge function estimation method for time series PCI and proved its asymptotic variance properties.
- Demonstrated the method's robustness to specific assumption violations through simulations and applied it to a real-world smartphone study of bipolar patients to analyze socio-environmental exposure.

## Limitations

The framework's validity relies on the existence of a bridge function and specific independence assumptions between proxies, which may not always hold in complex dynamical systems.

## Open Questions & Future Work

- [[doubly-robust-proximal-time-series]]
- [[non-stationary-proximal-causal-inference]]

## Key Concepts

- [[proximal-causal-inference-time-series]]: An extension of the proximal causal inference framework to time series data that leverages past and future observations as natural proxies for unmeasured confounders.

## Archivist Review

I approved the extension of Proximal Causal Inference to time series as a standalone concept because it addresses a fundamental bottleneck in observational longitudinal studies (unmeasured confounding). I also approved two open questions regarding double robustness and non-stationarity, as these represent the primary technical frontiers for making these causal methods reliable in real-world, dynamic environments like mobile health. No datasets were approved as the mentioned study was a specific application rather than a reusable benchmark.

### Approved Concepts
- Proximal Causal Inference for Time Series: Standard causal inference methods often fail in observational time series due to unmeasured confounding; this framework provides a formal identification strategy using the temporal structure of the data itself as proxies.

### Approved Open Questions
- Doubly Robust Proximal Time Series Estimation: Double robustness is a critical property for ensuring the reliability of causal inferences in complex observational time series where single bridge functions are difficult to validate.
- Proximal Inference for Non-Stationary Time Series: Mobile health data is inherently dynamic; methods that cannot account for non-stationarity risk producing biased or irrelevant treatment effect estimates.

## Links

- [Abstract](https://arxiv.org/abs/2610.22647)
- [PDF](https://arxiv.org/pdf/2610.22647)

