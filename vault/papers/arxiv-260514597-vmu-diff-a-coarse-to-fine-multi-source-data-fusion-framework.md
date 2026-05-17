---
# CSL-compatible fields
title: "VMU-Diff: A Coarse-to-fine Multi-source Data Fusion Framework for Precipitation Nowcasting"
author:
  - literal: "Chunlei Shi"
  - literal: "Hao Li"
  - literal: "Yufeng Zhu"
  - literal: "Boyu Liu"
  - literal: "Yongchao Feng"
  - literal: "Zengliang Zang"
  - literal: "Hongbin Wang"
  - literal: "Yanlan Yang"
  - literal: "Dan Niu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14597"

# Custom fields
paper_id: "2605.14597"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "jiangsu-swan"
concept_slugs:
  - "vmu-diff"
dataset_slugs:
  - "jiangsu-swan"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:16Z"
created_at: "2026-05-17T05:24:16Z"
---

# VMU-Diff: A Coarse-to-fine Multi-source Data Fusion Framework for Precipitation Nowcasting

**Authors**: Chunlei Shi, Hao Li, Yufeng Zhu, Boyu Liu, Yongchao Feng, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14597](https://arxiv.org/abs/2605.14597)

## Summary

VMU-Diff is a precipitation nowcasting framework that addresses the trade-off between deterministic blurriness and probabilistic artifacts in traditional methods. It utilizes a two-stage pipeline: first, a Vision Mamba Unet fuses multi-source radar and satellite data to establish global motion trends; second, a residual conditional diffusion model uses Mamba-based modules to refine fine-grained details. This coarse-to-fine approach significantly improves short-term forecast accuracy compared to existing single-source probabilistic and deterministic models.

## Key Contributions

- Introduces VMU-Diff, a coarse-to-fine framework that fuses multi-source radar and multi-band satellite data for precipitation nowcasting.
- Employs a two-stage approach using a deterministic Vision Mamba Unet for global motion dynamics followed by a residual conditional diffusion model for fine-grained detail reconstruction.
- Demonstrates significant improvements over state-of-the-art methods in short-term precipitation forecasting on the Jiangsu SWAN dataset.

## Key Concepts

- [[vmu-diff]]: A two-stage precipitation nowcasting framework that fuses multi-source meteorological data through coarse motion trend prediction and fine-grained residual diffusion refinement.

## Archivist Review

I approved the VMU-Diff framework as it introduces a novel hybrid architectural pattern that combines Vision Mamba-based deterministic trend modeling with residual diffusion-based refinement, which is highly relevant to spatiotemporal forecasting. The Jiangsu SWAN dataset was approved as a named meteorological benchmark central to the paper's empirical claims. I rejected the pluralized version of the dataset name in favor of a clean, singular slug.

### Approved Concepts
- VMU-Diff: The core contribution, providing a hybrid architecture that combines deterministic Vision Mamba-based global trend modeling with probabilistic residual diffusion-based detail generation.

### Rejected Candidates
- [dataset] Jiangsu SWAN datasets (`jiangsu-swan-datasets`) - duplicate_existing: The dataset was approved using the canonical slug format without the plural suffix.

## Datasets

- [[jiangsu-swan]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14597)
- [PDF](https://arxiv.org/pdf/2605.14597)

