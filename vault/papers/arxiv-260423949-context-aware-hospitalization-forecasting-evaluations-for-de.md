---
# CSL-compatible fields
title: "Context-Aware Hospitalization Forecasting Evaluations for Decision Support using LLMs"
author:
  - literal: "Rhea Makkuni"
  - literal: "Ananya Joshi"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23949"

# Custom fields
paper_id: "2604.23949"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "hybridarx"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:16:01Z"
created_at: "2026-04-28T05:16:01Z"
---

# Context-Aware Hospitalization Forecasting Evaluations for Decision Support using LLMs

**Authors**: Rhea Makkuni, Ananya Joshi
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.23949](https://arxiv.org/abs/2604.23949)

## Summary

This paper investigates the effective use of Large Language Models (LLMs) for real-time hospitalization forecasting in healthcare decision-making. The authors propose HybridARX, a hybrid architecture that integrates LLM-derived contextual information—such as demographic and geographic features—with structured time-series models. Through evaluations across 60 U.S. counties, they show that this hybrid approach yields more stable and better-calibrated forecasts than classical autoregressive models (ARX), especially when handling noisy real-world public health data. The findings emphasize that for non-stationary resource forecasting, embedding LLMs within structured pipelines is superior to direct, standalone LLM-based forecasting.

## Key Contributions

- Introduces HybridARX, a context-augmented pipeline that outperforms classical ARX models in hospitalization forecasting by embedding LLM-derived contextual features into structured time-series frameworks.
- Demonstrates that integrating LLM-derived signals into structured models improves forecast stability and calibration, particularly under noisy real-world data conditions.
- Establishes a decision-centric evaluation framework for healthcare forecasting, incorporating bias and lead-lag alignment alongside standard error metrics.

## Open Questions & Future Work

- [[identifying-reliable-leading-indicators-for-healthcare-demand]]

## Key Concepts

- [[hybridarx]]: A context-augmented hybrid forecasting architecture that embeds LLM-extracted features into structured autoregressive models for stable and calibrated prediction.

## Archivist Review

I approved the HybridARX architectural concept because it represents a distinct design pattern for bridging LLM capabilities with traditional structured forecasting. I also approved a refined version of the open question regarding the identification of reliable leading indicators, as it addresses the core bottleneck for decision-relevant forecasting in noisy environments. The evaluation framework was rejected as it describes a routine multi-metric approach common to many forecasting papers.

### Approved Concepts
- HybridARX: This hybrid architecture provides a reusable design pattern for integrating LLM-derived contextual features into structured time-series models to improve forecast stability in decision-critical domains.

### Approved Open Questions
- Identifying Reliable Leading Indicators: Without identified and validated leading indicators, even advanced hybrid forecasting models may fail to provide the proactive warnings necessary for resource allocation during healthcare crises.

## Links

- [Abstract](https://arxiv.org/abs/2604.23949)
- [PDF](https://arxiv.org/pdf/2604.23949)

