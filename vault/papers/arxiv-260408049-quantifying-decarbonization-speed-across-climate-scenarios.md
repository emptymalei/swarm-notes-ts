---
# CSL-compatible fields
title: "Quantifying Decarbonization Speed Across Climate Scenarios"
author:
  - literal: "Fangyuan Zhang"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08049"

# Custom fields
paper_id: "2604.08049"
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
processed_at: "2026-04-10T15:27:58Z"
created_at: "2026-04-10T15:27:58Z"
---

# Quantifying Decarbonization Speed Across Climate Scenarios

**Authors**: Fangyuan Zhang
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08049](https://arxiv.org/abs/2604.08049)

## Summary

This paper introduces a quantitative framework to measure the decarbonization speed inherent in narrative-based Integrated Assessment Model (IAM) climate scenarios. By mapping high-dimensional scenario time series into a single numerical metric, the author enables transparent cross-scenario comparisons consistent with established climate concentration pathways. The study analyzes 126 publicly available scenarios, providing both empirical and parametric distributions to characterize the range of mitigation policy speeds.

## Key Contributions

- Introduces a numerical metric to quantify the implied decarbonization speed of complex, narrative-based IAM climate scenarios.
- Enables transparent ranking and comparison of 126 climate scenarios across different representative concentration pathway (RCP) assumptions.
- Provides an empirical and parametric distribution analysis of decarbonization speeds, including bootstrap-based confidence intervals for key statistics.

## Open Questions & Future Work

- [[integrating-simplified-climate-metrics]]
- [[capturing-abrupt-policy-changes]]

## Archivist Review

The paper proposes a summary statistic (decarbonization speed) for high-dimensional IAM scenarios. Since this is a specific domain-driven metric rather than a generalized machine learning technique, I have rejected concepts derived from it to prevent cluttering the vault with application-specific metrics. I approved the open questions as they address fundamental challenges in bridging high-dimensional climate modeling with simplified, actionable interpretation for policy analysis, which is a recurring bottleneck in time-series forecasting for complex physical systems.

### Approved Open Questions
- Integrating Simplified Climate Metrics: Understanding the relationship between reduced metrics and high-dimensional model output is critical for accurately communicating the policy implications of climate scenarios to stakeholders who need to grasp both the overall trend and the specific drivers of a transition.
- Capturing Abrupt Policy Changes: Capturing the timing and severity of policy interventions is essential for accurate risk analysis, particularly in economic modeling where 'shock' events have non-linear consequences on transition pathways.

## Links

- [Abstract](https://arxiv.org/abs/2604.08049)
- [PDF](https://arxiv.org/pdf/2604.08049)

