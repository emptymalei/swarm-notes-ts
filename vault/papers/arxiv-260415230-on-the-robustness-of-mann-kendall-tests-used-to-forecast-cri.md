---
# CSL-compatible fields
title: "On the robustness of Mann-Kendall tests used to forecast critical transitions"
author:
  - literal: "Tristan Gamot"
  - literal: "Nils Thibeau--Sutre"
  - literal: "Tom J. M. Van Dooren"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15230"

# Custom fields
paper_id: "2604.15230"
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
processed_at: "2026-04-19T05:05:17Z"
created_at: "2026-04-19T05:05:17Z"
---

# On the robustness of Mann-Kendall tests used to forecast critical transitions

**Authors**: Tristan Gamot, Nils Thibeau--Sutre, Tom J. M. Van Dooren
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.15230](https://arxiv.org/abs/2604.15230)

## Summary

This paper investigates the statistical validity of using Mann-Kendall tests to detect early warning signals (EWS) of critical transitions in time series. The authors show that the reliance on asymptotic Gaussian distributions for the Mann-Kendall statistic fails when applied to EWS indicators, which are inherently autocorrelated. Their analysis reveals that these mismatches lead to severely inflated type I error rates, resulting in false positives for critical transition detection. Consequently, the authors conclude that Mann-Kendall tests are inappropriate for this task and suggest transitioning to more reliable statistical alternatives.

## Key Contributions

- Demonstrates that standard Mann-Kendall trend tests exhibit significantly inflated type I error rates when applied to early warning signals (EWS) due to induced autocorrelation.
- Provides a comprehensive evaluation showing that the Gaussian assumption of the Mann-Kendall statistic is invalid in the context of critical transition detection across common EWS scenarios.
- Formally recommends against using Mann-Kendall tests for critical transition forecasting and advocates for adopting alternative robust trend detection methods.

## Open Questions & Future Work

- [[non-parametric-ews-trend-significance]]

## Archivist Review

The paper provides a significant methodological critique of a common practice in critical transition forecasting. I have approved the open question regarding robust trend significance for EWS, as it highlights a persistent, unresolved issue with existing statistical benchmarks. I rejected the concept candidate because the paper functions primarily as a meta-analysis or debunking of an existing statistical test rather than introducing a novel, reusable modeling architecture or mechanism.

### Approved Open Questions
- Robust trend significance for EWS: Reliable detection of critical transitions is essential for early warning in ecological, climate, and medical domains. Current methodological reliance on Mann-Kendall tests leads to systematic false positives ('cry wolf' effects), undermining the utility of these forecasting frameworks.

### Rejected Candidates
- [concept] Mann-Kendall failure in EWS contexts (`mann-kendall-test-failure-ews`) - not_novel: The paper serves as a meta-analysis/debunking of a specific practice rather than proposing a new, reusable mechanism for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.15230)
- [PDF](https://arxiv.org/pdf/2604.15230)

