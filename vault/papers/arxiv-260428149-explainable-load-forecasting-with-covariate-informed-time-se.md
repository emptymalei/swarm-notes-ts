---
# CSL-compatible fields
title: "Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models"
author:
  - literal: "Matthias Hertel"
  - literal: "Alexandra Nikoltchovska"
  - literal: "Sebastian Pütz"
  - literal: "Ralf Mikut"
  - literal: "Benjamin Schäfer"
  - literal: "Veit Hagenmeyer"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28149"

# Custom fields
paper_id: "2604.28149"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-05-03T05:14:01Z"
created_at: "2026-05-03T05:14:01Z"
---

# Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models

**Authors**: Matthias Hertel, Alexandra Nikoltchovska, Sebastian Pütz, Ralf Mikut, Benjamin Schäfer, Veit Hagenmeyer
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28149](https://arxiv.org/abs/2604.28149)

## Summary

This paper addresses the transparency gap in Time Series Foundation Models (TSFMs) when applied to critical power grid infrastructure. The authors introduce an efficient SHAP-based explanation algorithm that exploits TSFMs' inherent flexibility in handling varied context lengths and covariate inputs. By applying this to Chronos-2 and TabPFN-TS in a zero-shot day-ahead load forecasting task, the study demonstrates that these models provide both competitive accuracy and domain-aligned explanations.

## Key Contributions

- Proposes an efficient SHAP-based explanation algorithm tailored for Time Series Foundation Models (TSFMs) by leveraging their flexibility in input context and covariate handling.
- Demonstrates that TSFMs (Chronos-2 and TabPFN-TS) achieve zero-shot performance competitive with domain-specific Transformers in day-ahead load forecasting for transmission system operators.
- Validates that SHAP explanations for TSFMs align with domain-specific causal factors such as weather and calendar patterns.

## Open Questions & Future Work

- [[efficient-shap-tsfm-estimation]]

## Archivist Review

I approved the open question regarding efficient SHAP estimation for TSFMs, as it identifies a clear, non-trivial bottleneck for deploying large foundation models in critical infrastructure. I rejected the concept candidate for the explanation algorithm itself, as it is a specific adaptation of existing SHAP techniques to the model's input masking capabilities rather than a standalone, re-usable fundamental contribution.

### Approved Open Questions
- Efficient SHAP for TSFMs: Scalable feature attribution is essential for the reliable deployment of foundation models in industrial settings, where black-box behavior is unacceptable.

### Rejected Candidates
- [concept] TSFM-Specific SHAP Explanation Algorithm (`tsfm-explanation-algorithm`) - not_novel: The proposed explanation method is an application of standard SHAP adapted to the model's interface rather than a novel conceptual framework for forecasting or model interpretation.

## Links

- [Abstract](https://arxiv.org/abs/2604.28149)
- [PDF](https://arxiv.org/pdf/2604.28149)

