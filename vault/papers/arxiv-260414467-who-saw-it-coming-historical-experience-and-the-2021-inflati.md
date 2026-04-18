---
# CSL-compatible fields
title: "Who Saw It Coming? Historical Experience and the 2021 Inflation Forecast Failure"
author:
  - literal: "Dalibor Stevanovic"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14467"

# Custom fields
paper_id: "2604.14467"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "causal-inference"
  - "llm-as-a-judge-for-time-series-explanations"
  - "historical-data-adjustment"
architectures:
  []
datasets:
  []
concept_slugs:
  - "experiential-priors"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:52:47Z"
created_at: "2026-04-18T04:52:47Z"
---

# Who Saw It Coming? Historical Experience and the 2021 Inflation Forecast Failure

**Authors**: Dalibor Stevanovic
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14467](https://arxiv.org/abs/2604.14467)

## Summary

This paper analyzes the 2021 U.S. inflation forecast failure, attributing it to a reliance on 'Great Moderation' era data that blinded models to supply-shock regimes. The author demonstrates that incorporating historical 1970s data through kernel weighting and similarity re-estimation significantly reduces forecast errors across multiple price indices. Furthermore, the study links these findings to experiential priors, confirming that both human agents and LLMs conditioned on older, experience-rich personas outperform those relying on more recent, low-volatility historical trends.

## Key Contributions

- Demonstrates that the 2021 U.S. inflation forecast failure resulted from sample composition bias (dominance of the Great Moderation) rather than functional form misspecification.
- Proposes three historically informed adjustments—intercept correction, 1970s-based similarity re-estimation, and kernel-weighted estimation—that significantly improve forecast accuracy across nine U.S. price indices.
- Validates the influence of experiential priors through both household survey analysis and a controlled LLM persona experiment, showing that training data source dominates model sophistication.

## Open Questions & Future Work

- [[systematic-historical-analogy-selection]]

## Key Concepts

- [[experiential-priors]]: A framework where forecasting performance is governed by the historical context encoded in training data or agent experience rather than model complexity.

## Archivist Review

The paper provides a compelling analysis of regime-specific forecast failure by distinguishing between model sophistication and historical training composition. I approved 'experiential-priors' as a valuable concept for understanding model behavior in non-stationary regimes and the open question regarding systematic historical analogy selection as a key bottleneck in applied macro-econometric forecasting. No other concepts or datasets were deemed sufficiently novel or central to merit vault entry.

### Approved Concepts
- Experiential Priors: Highlights that the origin of training data/experience is more critical than model architecture in regime-shifting forecasting contexts.

### Approved Open Questions
- Systematic Selection of Historical Analogues: The inability to automatically and reliably identify the most relevant historical period for forecasting during unique regime shifts is a primary challenge in macro-econometric modeling. This research highlights this limitation as a critical area for methodological advancement.

## Links

- [Abstract](https://arxiv.org/abs/2604.14467)
- [PDF](https://arxiv.org/pdf/2604.14467)

