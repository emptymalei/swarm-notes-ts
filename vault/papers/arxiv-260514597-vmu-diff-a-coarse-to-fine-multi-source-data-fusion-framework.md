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
  - "time-series"
  - "diffusion-models"
  - "spatio-temporal-forecasting"
  - "precipitation-nowcasting"
  - "mamba"
  - "data-fusion"
architectures:
  []
datasets:
  - "jiangsu-swan"
concept_slugs:
  - "vmu-diff"
dataset_slugs:
  - "jiangsu-swan"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:33Z"
created_at: "2026-05-16T05:12:33Z"
---

# VMU-Diff: A Coarse-to-fine Multi-source Data Fusion Framework for Precipitation Nowcasting

**Authors**: Chunlei Shi, Hao Li, Yufeng Zhu, Boyu Liu, Yongchao Feng, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14597](https://arxiv.org/abs/2605.14597)

## Summary

VMU-Diff is a two-stage precipitation nowcasting framework designed to overcome the limitations of blurring in deterministic models and spurious artifacts in diffusion models. The architecture employs a Vision Mamba Unet to fuse multi-source radar and satellite data, generating global motion trends in a coarse stage. These predictions are then refined through a second stage that uses a conditional residual diffusion model to reconstruct fine-grained details, yielding more accurate and detailed nowcasting results. Evaluation on the Jiangsu SWAN dataset indicates that this approach significantly enhances short-term forecasting quality.

## Key Contributions

- Introduces VMU-Diff, a coarse-to-fine framework that utilizes Vision Mamba blocks for multi-source (radar and satellite) fusion and global motion trend prediction.
- Develops a two-stage nowcasting pipeline that decouples global dynamic prediction from fine-grained detail refinement using residual conditional diffusion.
- Achieves improved short-term precipitation nowcasting performance on the Jiangsu SWAN dataset compared to existing deterministic and probabilistic baseline models.

## Key Concepts

- [[vmu-diff]]: A two-stage precipitation nowcasting framework that leverages a Vision Mamba-based coarse stage for global dynamics and a residual conditional diffusion-based fine stage for detail generation.

## Archivist Review

I approved the VMU-Diff framework as it provides a clear, reusable pattern for addressing the classic nowcasting tension between deterministic blurring and probabilistic artifacts. The Jiangsu SWAN dataset is approved as a representative regional precipitation benchmark mentioned as central to the paper's evaluation. All other candidates were rejected as redundant or specific implementations.

### Approved Concepts
- VMU-Diff: It represents a specific, reusable approach to decoupling global dynamic estimation and fine-grained refinement using state-space models and diffusion in spatio-temporal forecasting.

### Rejected Candidates
- [concept] Vision Mamba Unet and residual Diffusion (VMU-Diff) (`vmu-diff-framework`) - duplicate_existing: This is a duplicate of the approved VMU-Diff concept.

## Datasets

- [[jiangsu-swan]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14597)
- [PDF](https://arxiv.org/pdf/2605.14597)

