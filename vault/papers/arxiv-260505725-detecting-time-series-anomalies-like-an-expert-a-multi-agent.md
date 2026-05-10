---
# CSL-compatible fields
title: "Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers"
author:
  - literal: "Hyeongwon Kang"
  - literal: "Jeongseob Kim"
  - literal: "Jinwoo Park"
  - literal: "Pilsung Kang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05725"

# Custom fields
paper_id: "2605.05725"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series-anomaly-detection"
  - "multi-agent-systems"
  - "large-language-models"
  - "in-context-learning"
  - "explainable-ai"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sage-specialized-analyzer-group-for-expert-like-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:42Z"
created_at: "2026-05-10T05:20:42Z"
---

# Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers

**Authors**: Hyeongwon Kang, Jeongseob Kim, Jinwoo Park, Pilsung Kang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05725](https://arxiv.org/abs/2605.05725)

## Summary

SAGE addresses the limitations of monolithic LLM-based time-series anomaly detection by using a multi-agent architecture. The system decomposes analysis into four specialized modules—point, structural, seasonal, and pattern analyzers—that utilize numerical tools and visualizations to generate evidence. An evidence-grounded detector then synthesizes these diagnostics into comprehensive reports, while a synthetic in-context learning pipeline enables effective detection without requiring explicit anomaly labels.

## Key Contributions

- Proposed SAGE, a multi-agent framework that decomposes univariate time-series anomaly detection into specialized analyzers for point, structural, seasonal, and pattern anomalies.
- Implemented a novel synthetic in-context learning strategy that relies on normal-reference segments rather than labeled anomalous data.
- Achieved state-of-the-art average performance across three time-series benchmarks, demonstrating superior detection reliability and diagnostic output quality compared to baseline models.

## Open Questions & Future Work

- [[multi-agent-tsad-efficiency]]
- [[multivariate-extension-tsad]]

## Key Concepts

- [[sage-specialized-analyzer-group-for-expert-like-detection]]: A multi-agent LLM framework that decomposes time-series anomaly detection into specialized diagnostic analyzers and evidence-grounded consolidation.

## Archivist Review

I approved the multi-agent framework (SAGE) as a central, modular approach to time-series anomaly detection, and two open questions concerning its scalability and extension to multivariate settings. I applied a strict filter for reusability, rejecting any paper-local implementation components and ensuring the questions reflect genuine, substantial bottlenecks for LLM-based time-series diagnostics.

### Approved Concepts
- SAGE (Specialized Analyzer Group for Expert-like Detection): Introduces a modular, multi-agent decomposition approach to time-series anomaly detection, moving beyond monolithic LLM-based inference.

### Approved Open Questions
- Efficiency of Multi-Agent TSAD: Addressing these bottlenecks is essential for transitioning from research-grade prototypes to production-level anomaly detection systems where responsiveness and resource efficiency are critical.
- Multivariate Extension for TSAD: Multivariate anomaly detection is a standard requirement in industrial and financial applications, and extending diagnostic capabilities to such settings is necessary for broader practical utility.

## Links

- [Abstract](https://arxiv.org/abs/2605.05725)
- [PDF](https://arxiv.org/pdf/2605.05725)

