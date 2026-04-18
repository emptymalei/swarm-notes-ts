---
# CSL-compatible fields
title: "Assessing the Performance-Efficiency Trade-off of Foundation Models in Probabilistic Electricity Price Forecasting"
author:
  - literal: "Jan Niklas Lettner"
  - literal: "Hadeer El Ashhab"
  - literal: "Veit Hagenmeyer"
  - literal: "Benjamin Schäfer"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14739"

# Custom fields
paper_id: "2604.14739"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "time-series-forecasting"
  - "electricity-price-forecasting"
  - "foundation-models"
  - "benchmark"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:52:01Z"
created_at: "2026-04-18T04:52:01Z"
---

# Assessing the Performance-Efficiency Trade-off of Foundation Models in Probabilistic Electricity Price Forecasting

**Authors**: Jan Niklas Lettner, Hadeer El Ashhab, Veit Hagenmeyer, Benjamin Schäfer
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14739](https://arxiv.org/abs/2604.14739)

## Summary

This paper conducts a comparative performance-efficiency analysis of Time Series Foundation Models (TSFMs) versus task-specific deep learning architectures for probabilistic day-ahead electricity price forecasting (PEPF). While TSFMs like Moirai and ChronosX show strong general predictive performance in terms of calibration and uncertainty estimation, the study finds that highly-tuned task-specific models such as NHITS+QRA provide competitive or superior results with significantly lower computational overhead. The analysis underscores a critical performance-efficiency trade-off, suggesting that the adoption of TSFMs in energy markets should be carefully weighed against the marginal gains provided by domain-specialized, resource-efficient architectures.

## Key Contributions

- Systematic evaluation of foundation models (Moirai, ChronosX) against task-specific models (NHITS+QRA, Normalizing-Flow) for probabilistic day-ahead electricity price forecasting in European markets.
- TSFMs demonstrate superior performance in metrics like CRPS and Energy Score, yet exhibit higher computational costs and sensitivity to data availability compared to task-specific baselines.
- Evidence that task-specific NHITS+QRA models remain highly competitive and can outperform foundation models when augmented with domain-specific feature groups or cross-market few-shot adaptation.

## Open Questions & Future Work

- [[optimal-feature-selection-pepf]]
- [[calibrated-loss-functions-pepf]]

## Archivist Review

The paper provides a timely comparison between TSFMs and domain-specific models in the PEPF domain. I have approved the two open questions as they address fundamental bottlenecks in feature engineering and calibration for probabilistic energy forecasting. I rejected the concept candidate because the performance-efficiency trade-off is a high-level observation rather than a standalone, portable methodology.

### Approved Open Questions
- Optimal Feature Selection for PEPF: Developing systematic guidelines for feature selection is critical for balancing the computational costs of including high-dimensional exogenous data against the marginal gains in forecast accuracy for large-scale energy systems.
- Loss Functions for Calibrated PEPF: Proper calibration is essential for economic risk management in electricity markets, and current standardized loss functions may not fully capture the complexities of market-driven price volatility.

### Rejected Candidates
- [concept] Performance-Efficiency Trade-off in PEPF (`pepf-efficiency-tradeoff`) - not_reusable: This is a situational trade-off analysis rather than a reusable methodological concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.14739)
- [PDF](https://arxiv.org/pdf/2604.14739)

