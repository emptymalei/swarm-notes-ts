---
# CSL-compatible fields
title: "MICA: Multivariate Infini Compressive Attention for Time Series Forecasting"
author:
  - literal: "Willa Potosnak"
  - literal: "Nina Żukowska"
  - literal: "Michał Wiliński"
  - literal: "Dan Howarth, Ignacy Stępka"
  - literal: "Mononito Goswami"
  - literal: "Artur Dubrawski"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06473"

# Custom fields
paper_id: "2604.06473"
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
processed_at: "2026-04-09T04:56:00Z"
created_at: "2026-04-09T04:56:00Z"
---

# MICA: Multivariate Infini Compressive Attention for Time Series Forecasting

**Authors**: Willa Potosnak, Nina Żukowska, Michał Wiliński, Dan Howarth, Ignacy Stępka, Mononito Goswami, Artur Dubrawski
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06473](https://arxiv.org/abs/2604.06473)

## Summary

MICA addresses the scalability limitations of standard Transformer-based multivariate forecasting, where full cross-channel attention leads to prohibitive quadratic complexity. By applying compressive attention techniques to the channel dimension, the proposed architecture enables efficient modeling of inter-channel dependencies within a linear computational budget. Experimental results demonstrate that MICA consistently outperforms channel-independent baselines and other deep multivariate forecasting models on major benchmarks.

## Key Contributions

- Introduces Multivariate Infini Compressive Attention (MICA), which enables cross-channel dependency modeling in Transformers with linear complexity in both channel count and context length.
- Demonstrates that adding MICA to channel-independent backbones yields an average 5.4% improvement in forecast error across standard benchmarks, with gains reaching up to 25.4% on specific datasets.
- Establishes that MICA achieves state-of-the-art performance among multivariate deep learning baselines while maintaining superior scalability compared to standard quadratic cross-attention mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2604.06473)
- [PDF](https://arxiv.org/pdf/2604.06473)

