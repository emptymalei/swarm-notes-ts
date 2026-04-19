---
# CSL-compatible fields
title: "CSRA: Controlled Spectral Residual Augmentation for Robust Sepsis Prediction"
author:
  - literal: "Honglin Guo"
  - literal: "Rihao Chang"
  - literal: "He Jiao"
  - literal: "Weizhi Nie"
  - literal: "Zhongheng Zhang"
  - literal: "Yuehao Shen"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14532"

# Custom fields
paper_id: "2604.14532"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "sepsis-prediction"
  - "data-augmentation"
  - "icu-forecasting"
  - "spectral-analysis"
architectures:
  []
datasets:
  - "mimic-iv"
concept_slugs:
  - "controlled-spectral-residual-augmentation-csra"
dataset_slugs:
  - "mimic-iv"
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:06:14Z"
created_at: "2026-04-19T05:06:14Z"
---

# CSRA: Controlled Spectral Residual Augmentation for Robust Sepsis Prediction

**Authors**: Honglin Guo, Rihao Chang, He Jiao, Weizhi Nie, Zhongheng Zhang, Yuehao Shen
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14532](https://arxiv.org/abs/2604.14532)

## Summary

The paper introduces Controlled Spectral Residual Augmentation (CSRA), a framework designed to enhance sepsis prediction in ICU time series by generating clinically plausible trajectory variations. CSRA extracts system-level and global representations before applying input-adaptive residual perturbations in the spectral domain, regulated by anchor consistency and controller objectives. The framework demonstrates improved predictive performance and robustness across varied observation windows and prediction horizons on both the MIMIC-IV and ZiGongICUinfection datasets.

## Key Contributions

- Proposes CSRA, an input-adaptive spectral-domain data augmentation framework that improves sepsis prediction robustness.
- CSRA reduces regression error by 10.2% in MSE and 3.7% in MAE compared to non-augmentation baselines on MIMIC-IV.
- Demonstrates consistent robustness across varied observation windows, prediction horizons, training data scales, and external validation on the ZiGongICUinfection dataset.

## Open Questions & Future Work

- [[irregular-time-series-augmentation-robustness]]
- [[adaptive-system-aware-augmentation]]

## Key Concepts

- [[controlled-spectral-residual-augmentation-csra]]: An input-adaptive, spectral-domain data augmentation framework for ICU time series that uses anchor consistency and controller regularization to ensure clinical plausibility.

## Archivist Review

I approved the CSRA framework and two open questions regarding the scalability of augmentation to irregular data and adaptive system-level dependencies. The ZiGongICUinfection dataset was rejected as it appears to be a study-specific, niche dataset without sufficient evidence of broader impact or utility for the existing vault. Standardized academic naming and formatting were applied to all accepted entries.

### Approved Concepts
- Controlled Spectral Residual Augmentation (CSRA): Provides a novel, input-adaptive, spectral-domain data augmentation technique for ICU time series that ensures clinical plausibility through regularization.

### Approved Open Questions
- Augmentation for Irregular Data: Medical data is inherently irregular; without addressing this, models may not generalize to real-world deployment where monitoring frequencies vary significantly.
- Adaptive System-Aware Augmentation: Capturing dynamic physiological dependencies is essential for generating robust samples that correctly reflect the evolving interactions between clinical systems.

### Rejected Candidates
- [dataset] ZiGongICUinfection (`zigongicuinfection`) - low_impact: Insufficient information provided regarding the dataset's scale and general usage outside this specific study to warrant a permanent vault entry compared to established benchmarks.

## Datasets

- [[mimic-iv]]

## Links

- [Abstract](https://arxiv.org/abs/2604.14532)
- [PDF](https://arxiv.org/pdf/2604.14532)

