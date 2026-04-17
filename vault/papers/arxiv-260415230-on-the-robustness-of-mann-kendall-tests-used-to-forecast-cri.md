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
  - "time-series"
  - "forecasting"
  - "statistical-testing"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:04:47Z"
created_at: "2026-04-17T05:04:47Z"
---

# On the robustness of Mann-Kendall tests used to forecast critical transitions

**Authors**: Tristan Gamot, Nils Thibeau--Sutre, Tom J. M. Van Dooren
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.15230](https://arxiv.org/abs/2604.15230)

## Summary

This paper evaluates the robustness of Mann-Kendall trend tests when used to detect early warning signals (EWS) for critical transitions in time series. The authors demonstrate that the standard assumption of Gaussian asymptotic distribution for the Mann-Kendall statistic is invalid due to the autocorrelation inherent in common EWS indicators. This mismatch leads to significantly inflated type I error rates, suggesting that standard Mann-Kendall applications are unsuitable for reliable critical transition forecasting. The findings advocate for the abandonment of these tests in favor of more robust alternatives in transition detection tasks.

## Key Contributions

- Demonstrates that the theoretical Gaussian assumption of the Mann-Kendall test fails under the autocorrelation typically induced by early warning signal (EWS) indicators.
- Quantifies the inflation of type I error rates resulting from the application of standard Mann-Kendall trend tests to EWS time series.
- Provides empirical evidence that Mann-Kendall based critical transition forecasting is unreliable and recommends alternative statistical methods.

## Open Questions & Future Work

- [[robust-trend-testing-ews]]

## Archivist Review

The paper provides a critical, domain-specific evaluation of a standard statistical tool (Mann-Kendall) within the context of early warning signal (EWS) forecasting. I have approved the open question regarding the need for robust alternatives, as it addresses a significant identified failure in current forecasting methodologies. No new concepts were approved as the core contribution is a negative result regarding the applicability of an existing test rather than the proposal of a new, reusable mechanism.

### Approved Open Questions
- Robust trend testing for EWS: The paper demonstrates that current standard practices for identifying early warning signals lead to highly inflated Type I error rates, rendering existing automated critical transition detection unreliable. Establishing valid statistical protocols is essential for the reliable monitoring of complex systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.15230)
- [PDF](https://arxiv.org/pdf/2604.15230)

