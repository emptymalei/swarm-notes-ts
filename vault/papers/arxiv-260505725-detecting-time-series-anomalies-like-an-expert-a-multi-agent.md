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
  - "anomaly-detection"
  - "large-language-models"
  - "multi-agent-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sage-specialized-analyzer-group-for-expert-like-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:12:34Z"
created_at: "2026-05-09T05:12:34Z"
---

# Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers

**Authors**: Hyeongwon Kang, Jeongseob Kim, Jinwoo Park, Pilsung Kang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05725](https://arxiv.org/abs/2605.05725)

## Summary

SAGE is a multi-agent LLM framework designed to enhance the controllability and interpretability of univariate time-series anomaly detection. By decomposing the task into specialized analyzers—each utilizing targeted numerical tools and visualizations—the framework generates evidence-grounded detection records and analyst-facing reports. SAGE avoids reliance on labeled anomalous segments by constructing synthetic in-context examples from normal training data, consistently outperforming existing machine learning and language-model-based baselines across three benchmark datasets.

## Key Contributions

- Proposes SAGE, a multi-agent framework decomposing anomaly detection into four specialized analyzers for point, structural, seasonal, and pattern anomalies.
- Implements evidence-grounded anomaly detection using family-specific numerical tools and diagnostic visualizations.
- Achieves state-of-the-art performance on three standard time-series anomaly detection benchmarks while improving interpretability through structured diagnostic reporting.

## Open Questions & Future Work

- [[multivariate-agentic-tsad-scalability-bottlenecks]]

## Key Concepts

- [[sage-specialized-analyzer-group-for-expert-like-detection]]: A multi-agent framework that decomposes time-series anomaly detection into specialized analyzers for different anomaly types, resulting in evidence-grounded diagnostic reports.

## Archivist Review

I approved the SAGE framework concept as it introduces a reusable multi-agent paradigm for time-series analysis tasks by decomposing analysis into specialized numerical sub-tasks. The open question was approved after condensing the scope to focus on the core scalability bottlenecks (multivariate extension and latency) inherent in agentic time-series systems, aligning with the vault's standards for substantial research challenges. No datasets were approved as they were mentioned only in passing as benchmarks.

### Approved Concepts
- SAGE (Specialized Analyzer Group for Expert-like Detection): Provides a central multi-agent architecture for structured, expert-like anomaly diagnosis by decomposing detection into specialized, numerical-tool-backed analyzers.

### Approved Open Questions
- Multivariate Agentic TSAD Bottlenecks: These issues are central to the scalability and practical reliability of agentic TSAD frameworks in industrial or critical monitoring settings.

## Links

- [Abstract](https://arxiv.org/abs/2605.05725)
- [PDF](https://arxiv.org/pdf/2605.05725)

