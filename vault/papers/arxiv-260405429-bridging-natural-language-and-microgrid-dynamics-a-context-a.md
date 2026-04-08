---
# CSL-compatible fields
title: "Bridging Natural Language and Microgrid Dynamics: A Context-Aware Simulator and Dataset"
author:
  - literal: "Tinko Sebastian Bartels"
  - literal: "Ruixiang Wu"
  - literal: "Xinyu Lu"
  - literal: "Yikai Lu"
  - literal: "Fanzeng Xia"
  - literal: "Haoxiang Yang"
  - literal: "Yue Chen"
  - literal: "Tongxin Li"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05429"

# Custom fields
paper_id: "2604.05429"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  - "opencem-dataset"
concept_slugs:
  - "opencem-simulator-and-dataset"
dataset_slugs:
  - "opencem-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:15Z"
created_at: "2026-04-08T04:56:15Z"
---

# Bridging Natural Language and Microgrid Dynamics: A Context-Aware Simulator and Dataset

**Authors**: Tinko Sebastian Bartels, Ruixiang Wu, Xinyu Lu, Yikai Lu, Fanzeng Xia, Haoxiang Yang, Yue Chen, Tongxin Li
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05429](https://arxiv.org/abs/2604.05429)

## Summary

The paper introduces OpenCEM, an open-source digital twin and dataset designed to bridge the gap between traditional numerical time-series energy management and unstructured human-generated context. By integrating language-based inputs—such as event schedules and system logs—with quantitative renewable energy dynamics, the platform enables more intelligent, context-aware decision-making. The authors provide a hybrid simulator architecture that supports high-fidelity validation of LLM-driven control algorithms and energy prediction models. Their results demonstrate the platform's utility in practical microgrid scenarios, including advanced load forecasting and online battery optimization.

## Key Contributions

- Introduces OpenCEM, the first open-source digital twin for integrating unstructured textual context with quantitative microgrid energy dynamics.
- Provides a language-rich, aligned dataset from a real-world PV-and-battery microgrid installation.
- Demonstrates superior capabilities in context-aware load forecasting and optimal battery charging control through a hybrid physics-based and data-driven simulator architecture.

## Open Questions & Future Work

- [[high-fidelity-surrogate-modeling-for-microgrids]]

## Key Concepts

- [[opencem-simulator-and-dataset]]: An open-source digital twin platform that integrates unstructured linguistic context with quantitative renewable energy time-series data for microgrid management.

## Archivist Review

I approved the OpenCEM platform and its associated dataset, as they provide a significant contribution toward multi-modal (text-to-time-series) energy systems research. The open question regarding surrogate model fidelity was approved because it addresses a critical limitation in current digital twin environments for microgrids. Other candidates were deemed redundant or specific to this paper's implementation.

### Approved Concepts
- OpenCEM Simulator and Dataset: It establishes a framework for multi-modal energy management by integrating unstructured natural language context with quantitative microgrid time-series, which is a novel direction for grid-level simulation.

### Approved Open Questions
- High-fidelity surrogate modeling for microgrids: Improving the fidelity of physics-based models is essential for bridging the gap between digital twins and real-world microgrid operational behavior, which is critical for reliable control strategy validation.

## Datasets

- [[opencem-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.05429)
- [PDF](https://arxiv.org/pdf/2604.05429)

