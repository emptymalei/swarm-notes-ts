---
# CSL-compatible fields
title: "QuITE: Query-Based Irregular Time Series Embedding"
author:
  - literal: "JungHoon Lim"
issued:
  date-parts:
    - [2026, 5, 27]
url: "https://arxiv.org/abs/2605.28166"

# Custom fields
paper_id: "2605.28166"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "representation-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quite-query-based-irregular-time-series-embedding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-28T05:32:10Z"
created_at: "2026-05-28T05:32:10Z"
---

# QuITE: Query-Based Irregular Time Series Embedding

**Authors**: JungHoon Lim
**Date**: 2026-05-27
**Paper ID**: [arxiv:2605.28166](https://arxiv.org/abs/2605.28166)

## Summary

QuITE addresses the challenge of modeling irregular multivariate time series (IMTS) by introducing a plug-and-play embedding module that avoids the common pitfalls of artificial value interpolation. By utilizing learnable query tokens within a self-attention layer, the module transforms irregular inputs into backbone-compatible latent representations. This approach preserves temporal dynamics and allows standard multivariate time series models to be applied directly to irregular data, significantly improving performance across forecasting and classification tasks.

## Key Contributions

- Introduces QuITE, a plug-and-play embedding module that converts irregular multivariate time series into uniform latent representations using learnable query tokens and self-attention.
- Eliminates the need for artificial data imputation or complex, irregular-specific backbone modifications.
- Achieves relative performance gains of up to 54.7% in forecasting and 15.8% in classification across multiple MTS backbones and datasets.

## Key Concepts

- [[quite-query-based-irregular-time-series-embedding]]: A plug-and-play embedding module that uses learnable query tokens and self-attention to transform irregular multivariate time series into uniform latent representations.

## Archivist Review

The paper introduces a clean, plug-and-play architectural module for handling irregular time series data. QuITE is approved as a concept because it addresses a fundamental representation challenge in time series modeling—bridging irregular sampling and backbone architectures—without the typical overhead of data imputation or invasive model modification. No datasets or open questions were proposed, and none were deemed sufficiently critical as standalone contributions based on the provided text.

### Approved Concepts
- QuITE (Query-Based Irregular Time Series Embedding): It provides a novel, backbone-agnostic way to handle irregular time series without requiring imputation or specialized architectures.

## Links

- [Abstract](https://arxiv.org/abs/2605.28166)
- [PDF](https://arxiv.org/pdf/2605.28166)

