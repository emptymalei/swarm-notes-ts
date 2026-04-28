---
# CSL-compatible fields
title: "IMPA-Net: Meteorology-Aware Multi-Scale Attention and Dynamic Loss for Extreme Convective Radar Nowcasting"
author:
  - literal: "Haofei Cui"
  - literal: "Guangxin He"
  - literal: "Juanzhen Sun"
  - literal: "Jingjia Luo"
  - literal: "Haonan Chen"
  - literal: "Xiaoran Zhuang"
  - literal: "Mingxuan Chen"
  - literal: "Xian Xiao"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24224"

# Custom fields
paper_id: "2604.24224"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "meteorology"
  - "attention-mechanisms"
  - "loss-functions"
  - "radar-nowcasting"
  - "spatiotemporal-prediction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "meteorologically-aware-dynamic-loss"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:52Z"
created_at: "2026-04-28T05:14:52Z"
---

# IMPA-Net: Meteorology-Aware Multi-Scale Attention and Dynamic Loss for Extreme Convective Radar Nowcasting

**Authors**: Haofei Cui, Guangxin He, Juanzhen Sun, Jingjia Luo, Haonan Chen, Xiaoran Zhuang, Mingxuan Chen, Xian Xiao
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24224](https://arxiv.org/abs/2604.24224)

## Summary

IMPA-Net is a deep learning framework designed for 0-2 hour convective radar nowcasting, addressing the common issue of overly smooth forecasts that mask critical hazard intensity. The model integrates a spatial mixer for mesoscale feature reorganization, a multi-scale predictive attention module for spatiotemporal translation, and a meteorologically-informed dynamic loss function to prioritize severe storm echoes. Experimental results demonstrate substantial improvements in Heidke Skill Scores and spectral energy preservation over standard baselines like SimVP and pySTEPS.

## Key Contributions

- Introduced IMPA-Net, which utilizes meteorologically-informed input reorganization and multi-scale attention to improve convective radar nowcasting.
- Developed a Meteorologically-Aware Dynamic Loss that significantly mitigates regression-to-the-mean and improves Heidke Skill Scores for high-intensity echoes (≥45 dBZ) compared to baselines like SimVP.
- Demonstrated superior performance in preserving spectral energy across mesoscale bands and better trade-offs between detection and false-alarm control relative to traditional methods like pySTEPS.

## Limitations

Generalizability to other orographic and climatic regions remains to be tested, as the current evaluation is limited to a convective regime in eastern China.

## Open Questions & Future Work

- [[cross-region-generalizability-of-meteorology-informed-forecasting]]

## Key Concepts

- [[meteorologically-aware-dynamic-loss]]: A three-level asymmetric loss function weighting strategy designed to preserve high-intensity signals during spatiotemporal forecasting.

## Archivist Review

The Meteorologically-Aware Dynamic Loss was approved as it provides a clear, reusable approach to mitigating regression-to-the-mean in extreme event forecasting. The open question regarding cross-region generalizability addresses a fundamental limitation in the current deployment of meteorological models. Other architectural components were rejected as they represent specific local implementations rather than broader, novel algorithmic contributions.

### Approved Concepts
- Meteorologically-Aware Dynamic Loss: Addresses the critical ML forecasting issue of regression-to-the-mean (oversmoothing) by incorporating meteorological constraints into the loss function optimization process.

### Approved Open Questions
- Cross-region Meteorology Forecast Generalization: Evaluating cross-region generalizability is vital for deploying nowcasting models in diverse geographic environments where convective dynamics vary significantly.

### Rejected Candidates
- [concept] Spatial Mixer (`spatial-mixer`) - paper_local: The described spatial mixer is a parameter-free channel permutation module, which is too paper-local and simple to qualify as a foundational concept.
- [concept] Integrated Multi-scale Predictive Attention Module (`integrated-multi-scale-predictive-attention-module`) - subcomponent_of_broader_mechanism: This module is a specific architectural subcomponent designed for the paper's framework, failing the requirement for a broader reusable forecasting mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.24224)
- [PDF](https://arxiv.org/pdf/2604.24224)

