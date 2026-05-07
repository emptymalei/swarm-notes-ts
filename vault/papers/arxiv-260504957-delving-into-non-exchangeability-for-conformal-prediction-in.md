---
# CSL-compatible fields
title: "Delving into Non-Exchangeability for Conformal Prediction in Graph-Structured Multivariate Time Series"
author:
  - literal: "Ruichao Guo"
  - literal: "Xingyao Han"
  - literal: "Luo Wenshui"
  - literal: "Zhe Liu"
  - literal: "Chen Gong"
  - literal: "Hesheng Wang"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04957"

# Custom fields
paper_id: "2605.04957"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "uncertainty-quantification"
  - "conformal-prediction"
  - "graph-neural-networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectral-graph-conditional-exchangeability"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:14:20Z"
created_at: "2026-05-07T05:14:20Z"
---

# Delving into Non-Exchangeability for Conformal Prediction in Graph-Structured Multivariate Time Series

**Authors**: Ruichao Guo, Xingyao Han, Luo Wenshui, Zhe Liu, Chen Gong, Hesheng Wang
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04957](https://arxiv.org/abs/2605.04957)

## Summary

The paper addresses the failure of standard conformal prediction (CP) in graph-structured multivariate time series due to inherent non-exchangeability caused by cross-node coupling. The authors characterize this coupling using spectral graph theory, noting that low-frequency components contain global trends while high-frequency components satisfy the exchangeability condition. They propose Spectral Graph Conditional Exchangeability (SGCE) and a corresponding implementation, SCALE, which uses graph wavelets to perform conformal prediction on conditioned high-frequency residuals, achieving superior coverage and efficiency in traffic forecasting tasks.

## Key Contributions

- Introduces Spectral Graph Conditional Exchangeability (SGCE) to rigorously address the non-exchangeability challenge in graph-structured multivariate time series.
- Proposes Spectral Conformal prediction via wAveLEt transform (SCALE), a framework that utilizes graph wavelets to isolate and conformalize high-frequency residuals.
- Demonstrates that SCALE improves coverage-efficiency trade-offs on traffic forecasting benchmarks compared to existing conformal prediction baselines.

## Open Questions & Future Work

- [[non-exchangeability-in-graph-conformal-prediction]]

## Key Concepts

- [[spectral-graph-conditional-exchangeability]]: A theoretical framework for enabling conformal prediction in graph-structured time series by conditioning exchangeable high-frequency components on non-exchangeable low-frequency trends.

## Archivist Review

I approved Spectral Graph Conditional Exchangeability as a novel concept that provides a theoretical bridge between spectral graph theory and conformal prediction. I rejected SCALE as it is an architectural instantiation of the SGCE concept. I replaced the candidate open question with a more precise version focused on the broader theoretical limitations of achieving exchangeability in dynamic graphs.

### Approved Concepts
- Spectral Graph Conditional Exchangeability: It addresses the fundamental theoretical barrier of applying conformal prediction to non-exchangeable graph-structured time series.

### Approved Open Questions
- Non-exchangeability in graph conformal prediction: This question addresses the fundamental tension between strict coverage guarantees and the pervasive non-exchangeability found in real-world dynamical systems.

### Rejected Candidates
- [concept] SCALE (`scale`) - subcomponent_of_broader_mechanism: This is an architectural implementation (framework) of the broader concept (SGCE) and is better viewed as the system instantiation rather than a distinct conceptual building block.
- [open_question] Spectral Conformal Prediction Limitations (`spectral-graph-conformal-limitations`) - duplicate_existing: This is a slight re-packaging of the problem statement and lacks the specific theoretical depth required for a tracking question; replaced by a more precise research question.

## Links

- [Abstract](https://arxiv.org/abs/2605.04957)
- [PDF](https://arxiv.org/pdf/2605.04957)

