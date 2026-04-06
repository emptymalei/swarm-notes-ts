---
# CSL-compatible fields
title: "Transfer Learning for Loan Recovery Prediction under Distribution Shifts with Heterogeneous Feature Spaces"
author:
  - literal: "Christopher Gerling"
  - literal: "Hanqiu Peng"
  - literal: "Ying Chen"
  - literal: "Stefan Lessmann"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02832"

# Custom fields
paper_id: "2604.02832"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "global-credit-data"
concept_slugs:
  []
dataset_slugs:
  - "global-credit-data"
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:02:56Z"
created_at: "2026-04-06T05:02:56Z"
---

# Transfer Learning for Loan Recovery Prediction under Distribution Shifts with Heterogeneous Feature Spaces

**Authors**: Christopher Gerling, Hanqiu Peng, Ying Chen, Stefan Lessmann
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02832](https://arxiv.org/abs/2604.02832)

## Summary

This paper addresses data scarcity in loan recovery rate (RR) forecasting by proposing the FT-MDN-Transformer, a mixture-density tabular Transformer designed for transfer learning across heterogeneous feature spaces. The model leverages source-domain knowledge to improve RR predictions in data-constrained target domains, producing both point estimates and predictive distributions. Evaluation on simulation studies and real-world credit datasets demonstrates significant robustness to covariate and conditional shifts compared to traditional baselines.

## Key Contributions

- Introduces FT-MDN-Transformer, a mixture-density tabular Transformer architecture designed for transfer learning under heterogeneous feature spaces.
- Demonstrates superior performance in recovery rate forecasting with limited target-domain data, particularly under covariate and conditional shifts.
- Provides probabilistic forecasts that accurately track empirical recovery distributions, outperforming point-prediction baselines in credit risk scenarios.

## Open Questions & Future Work

- [[label-shift-correction-transfer-learning]]

## Archivist Review

The paper presents a specialized Transformer variant for credit recovery forecasting. While the architecture (FT-MDN-Transformer) is a useful implementation, it is essentially a domain-specific application of known techniques (Mixture Density Networks + Tabular Transformers). The open question regarding label shift correction is approved as it addresses a persistent, high-impact bottleneck in transfer learning for tabular/financial data. Global Credit Data (GCD) is approved as a key domain-specific dataset for this line of research.

### Approved Open Questions
- Label Shift Correction Mechanisms: Label shift is identified as the most significant hurdle for transfer learning effectiveness in financial forecasting scenarios, and current architectures often lack mechanisms to explicitly mitigate this type of distributional drift.

### Rejected Candidates
- [concept] FT-MDN-Transformer (`ft-mdn-transformer`) - paper_local: This is a paper-specific model architecture rather than a foundational methodology or concept.

## Datasets

- [[global-credit-data]]

## Links

- [Abstract](https://arxiv.org/abs/2604.02832)
- [PDF](https://arxiv.org/pdf/2604.02832)

