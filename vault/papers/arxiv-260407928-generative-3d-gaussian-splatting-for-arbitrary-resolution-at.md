---
# CSL-compatible fields
title: "Generative 3D Gaussian Splatting for Arbitrary-Resolution Atmospheric Downscaling and Forecasting"
author:
  - literal: "Tao Hana"
  - literal: "Zhibin Wen"
  - literal: "Zhenghao Chen"
  - literal: "Fenghua Lin"
  - literal: "Junyu Gao"
  - literal: "Song Guo"
  - literal: "Lei Bai"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07928"

# Custom fields
paper_id: "2604.07928"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "downscaling"
  - "vision-transformer"
  - "3d-gaussian-splatting"
architectures:
  []
datasets:
  - "era5"
  - "cmip6"
concept_slugs:
  - "scale-aware-attention-module"
dataset_slugs:
  - "era5"
  - "cmip6"
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:28:20Z"
created_at: "2026-04-10T15:28:20Z"
---

# Generative 3D Gaussian Splatting for Arbitrary-Resolution Atmospheric Downscaling and Forecasting

**Authors**: Tao Hana, Zhibin Wen, Zhenghao Chen, Fenghua Lin, Junyu Gao, Song Guo, Lei Bai
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07928](https://arxiv.org/abs/2604.07928)

## Summary

The GSSA-ViT framework addresses the computational bottleneck of high-resolution numerical weather prediction by representing atmospheric data as 3D Gaussians. By learning to predict Gaussian parameters, the model achieves superior multi-scale adaptability and arbitrary-resolution output. A novel scale-aware attention mechanism further enables the integration of information across varying downscaling ratios, outperforming traditional approaches on ERA5 and CMIP6 datasets.

## Key Contributions

- Introduced GSSA-ViT, a 3D Gaussian splatting framework for unified arbitrary-resolution atmospheric forecasting and downscaling.
- Developed a generative 3D Gaussian prediction scheme to estimate covariance, attributes, and opacity for unseen atmospheric samples.
- Designed a scale-aware attention module that enables cross-scale dependency capture for continuous resolution adaptation across ERA5 and CMIP6 benchmarks.

## Open Questions & Future Work

- [[mitigating-autoregressive-forecasting-error-accumulation]]

## Key Concepts

- [[scale-aware-attention-module]]: An attention-based mechanism that enables continuous resolution adaptation by capturing cross-scale dependencies in high-dimensional atmospheric fields.

## Archivist Review

I have approved the 'Scale-Aware Attention Module' as a reusable mechanism for multi-scale forecasting and the 'Mitigating Autoregressive Forecasting Error Accumulation' open question, as it highlights a persistent, critical challenge in the field. The proposed model 'GSSA-ViT' was rejected as it is a specific implementation instance rather than a foundational concept. The datasets ERA5 and CMIP6 were approved as they are canonical benchmarks in atmospheric time-series modeling.

### Approved Concepts
- Scale-Aware Attention Module: It provides a mechanism for cross-scale dependency modeling which is critical for arbitrary-resolution downscaling tasks in atmospheric forecasting.

### Approved Open Questions
- Mitigating Autoregressive Forecasting Error Accumulation: Cumulative error remains the primary bottleneck for extending lead-time accuracy in AI-based atmospheric and spatiotemporal prediction.

### Rejected Candidates
- [concept] GSSA-ViT (`gssa-vit`) - paper_local: This is a specific model architecture rather than a reusable architectural pattern or mechanism.
- [open_question] Efficient Sparse Attention for Forecasting (`efficient-sparse-attention-for-global-forecasting`) - low_impact: This is a generic future work direction regarding computational efficiency and lacks a specific, novel research path.

## Datasets

- [[era5]]
- [[cmip6]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07928)
- [PDF](https://arxiv.org/pdf/2604.07928)

