---
# CSL-compatible fields
title: "Ratio of Quantiles Indicates Burstiness with Fewer False Negatives than the Conventional Burstiness Parameter"
author:
  - literal: "Joshua Z. Stadlan"
  - literal: "Michelle Birkett"
  - literal: "Jason H. Rife"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05188"

# Custom fields
paper_id: "2604.05188"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "burstiness-tail-based-index-bti"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:57:17Z"
created_at: "2026-04-08T04:57:17Z"
---

# Ratio of Quantiles Indicates Burstiness with Fewer False Negatives than the Conventional Burstiness Parameter

**Authors**: Joshua Z. Stadlan, Michelle Birkett, Jason H. Rife
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05188](https://arxiv.org/abs/2604.05188)

## Summary

This paper addresses the limitations of the canonical Burstiness Parameter (BP) in detecting bursty behavior in temporal signals, specifically its propensity for false negatives in power-law distributions. The authors introduce the Burstiness Tail-based Index (BTI), which utilizes ratios of quantile differences to provide a more accurate characterization of burstiness. Evaluation through analytical derivation and simulated sampling confirms that BTI is more robust to small sample sizes and constrained observation windows than BP. The practical utility of the metric is demonstrated in a case study of human activity data, where BTI shifts the interpretation of bursty timescales compared to traditional metrics.

## Key Contributions

- Introduces the Burstiness Tail-based Index (BTI), a metric based on quantile ratios that reduces false negatives compared to the canonical Burstiness Parameter (BP).
- Demonstrates analytically and through simulation that BTI correctly identifies bursty distributions (e.g., power laws) where BP fails.
- Shows BTI's superior robustness to limited sample sizes and shorter observation windows, influencing the interpretation of timescales in human activity data.

## Key Concepts

- [[burstiness-tail-based-index-bti]]: A burstiness metric based on the ratio of quantile differences designed to reduce false negatives in moderate sampling conditions.

## Archivist Review

I approved the Burstiness Tail-based Index (BTI) because it replaces a legacy statistical metric (the canonical Burstiness Parameter) with a more robust, quantile-based alternative that is explicitly designed to handle common issues in temporal data like limited sample sizes and power-law tails. This represents a significant contribution to the toolset for temporal signal analysis. No other concepts or open questions were proposed, and no datasets met the criteria for inclusion.

### Approved Concepts
- Burstiness Tail-based Index (BTI): Provides a more robust, statistically sound method for characterizing temporal burstiness than the conventional Burstiness Parameter, particularly for power-law distributions.

## Links

- [Abstract](https://arxiv.org/abs/2604.05188)
- [PDF](https://arxiv.org/pdf/2604.05188)

