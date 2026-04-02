---
# CSL-compatible fields
title: "DLWM: Dual Latent World Models enable Holistic Gaussian-centric Pre-training in Autonomous Driving"
author:
  - literal: "Yiyao Zhu"
  - literal: "Ying Xue"
  - literal: "Haiming Zhang"
  - literal: "Guangfeng Jiang"
  - literal: "Wending Zhou"
  - literal: "Xu Yan"
  - literal: "Jiantao Gao"
  - literal: "Yingjie Cai"
  - literal: "Bingbing Liu"
  - literal: "Zhen Li"
  - literal: "Shaojie Shen"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00969"

# Custom fields
paper_id: "2604.00969"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  - "nuscenes"
  - "surroundocc"
concept_slugs:
  - "gaussian-centric-autonomous-driving"
dataset_slugs:
  - "nuscenes"
  - "surroundocc"
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:37:30Z"
created_at: "2026-04-02T05:37:30Z"
---

# DLWM: Dual Latent World Models enable Holistic Gaussian-centric Pre-training in Autonomous Driving

**Authors**: Yiyao Zhu, Ying Xue, Haiming Zhang, Guangfeng Jiang, Wending Zhou, Xu Yan, Jiantao Gao, Yingjie Cai, Bingbing Liu, Zhen Li, Shaojie Shen
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00969](https://arxiv.org/abs/2604.00969)

## Summary

DLWM is a two-stage pre-training framework that utilizes dual latent world models to learn temporal dynamics for Gaussian-centric autonomous driving. The first stage reconstructs semantic and depth information via 3D Gaussians, while the second stage employs Gaussian-flow-guided and ego-planning-guided latent prediction to improve downstream occupancy forecasting and motion planning. This approach provides a holistic representation for sparse scene understanding, demonstrating significant gains over traditional BEV and query-based methods on the nuScenes and SurroundOcc datasets.

## Key Contributions

- Introduces DLWM, a dual latent world model framework for Gaussian-centric autonomous driving pre-training.
- Implements Gaussian-flow-guided latent prediction for improved 3D occupancy perception and forecasting.
- Integrates ego-planning-guided latent prediction to enhance motion planning performance.
- Achieves state-of-the-art performance on SurroundOcc and nuScenes for occupancy and planning benchmarks.

## Open Questions & Future Work

- [[gaussian-query-temporal-correspondence]]

## Key Concepts

- [[gaussian-centric-autonomous-driving]]: A scene representation paradigm that describes autonomous driving environments using sparse 3D semantic Gaussians rather than dense BEV grids or query sets.

## Archivist Review

I have approved the core paradigm 'Gaussian-centric Autonomous Driving' and the related open question concerning temporal correspondence of sparse primitives. I have also added the two primary benchmarks used for evaluation. Other concepts like 'Dual Latent World Models' were rejected as they appear specific to the architectural implementation of the paper rather than broadly reusable methodological primitives.

### Approved Concepts
- Gaussian-centric Autonomous Driving: Gaussian representations are emerging as a highly efficient alternative to dense BEV or query-based representations in autonomous driving scenes, requiring a distinct conceptual entry.

### Approved Open Questions
- Temporal Correspondence of Gaussians: Direct temporal modeling on Gaussian primitives could bypass the inefficiencies of intermediate BEV-based representations, improving both compute performance and feature fidelity in long-horizon forecasting.

## Datasets

- [[nuscenes]]
- [[surroundocc]]

## Links

- [Abstract](https://arxiv.org/abs/2604.00969)
- [PDF](https://arxiv.org/pdf/2604.00969)

