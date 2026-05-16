---
# CSL-compatible fields
title: "MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting"
author:
  - literal: "Chunlei Shi"
  - literal: "Cui Wu"
  - literal: "Xiang Xu"
  - literal: "Hao Li"
  - literal: "Ni Fan"
  - literal: "Xue Han, Yongchao Feng, Yufeng Zhu, Boyu Liu, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14606"

# Custom fields
paper_id: "2605.14606"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "spatiotemporal-forecasting"
  - "meteorological-forecasting"
  - "attention-mechanisms"
  - "state-space-models"
  - "nowcasting"
architectures:
  - "Mamba"
  - "Transformer"
datasets:
  []
concept_slugs:
  - "mambarain"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:21Z"
created_at: "2026-05-16T05:12:21Z"
---

# MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting

**Authors**: Chunlei Shi, Cui Wu, Xiang Xu, Hao Li, Ni Fan, Xue Han, Yongchao Feng, Yufeng Zhu, Boyu Liu, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14606](https://arxiv.org/abs/2605.14606)

## Summary

MambaRain is a novel multi-scale encoder-decoder framework designed for 0-3 hour precipitation nowcasting. It addresses the performance degradation of traditional deterministic models at long horizons by synergistically combining Mamba's linear-complexity temporal state space modeling with self-attention for spatial correlation. To further enhance predictive quality, the authors introduce a spectral loss formulation to maintain fine-scale motion details and mitigate blurring in chaotic weather systems. Results show significant accuracy improvements, particularly in the critical 2-3 hour forecasting range.

## Key Contributions

- Introduces MambaRain, a hybrid architecture combining Mamba selective state space mechanisms with self-attention for improved long-range spatiotemporal precipitation modeling.
- Extends viable precipitation nowcasting horizons from the standard 0-2 hours to 0-3 hours with significant accuracy gains, particularly in the 2-3 hour window.
- Proposes a spectral loss formulation to mitigate blurring artifacts and better preserve fine-scale motion details in chaotic meteorological data.

## Open Questions & Future Work

- [[probabilistic-nowcasting-uncertainty-modeling]]

## Key Concepts

- [[mambarain]]: A hybrid spatiotemporal forecasting architecture that combines Mamba's linear-complexity temporal state space modeling with self-attention for explicit spatial correlation capture.

## Archivist Review

I approved the MambaRain architecture as a representative pattern for mixing state-space models and attention in spatiotemporal domains, as this is a prominent emerging trend. The spectral loss was rejected as it is a common, localized technique within meteorological deep learning rather than a standalone concept. I maintained the proposed open question as it captures a fundamental limitation of current deterministic nowcasting benchmarks.

### Approved Concepts
- MambaRain: It introduces a novel hybrid architectural pattern that decouples and addresses long-range temporal dependencies using linear-complexity models while maintaining spatial integrity via attention.

### Approved Open Questions
- Probabilistic Nowcasting Uncertainty Modeling: Addressing the regression-to-the-mean effect is fundamental to improving the meteorological realism and operational utility of nowcasting, as blurred predictions are particularly misleading for high-intensity, short-duration convective hazards.

### Rejected Candidates
- [concept] Spectral Loss Formulation (`spectral-loss-formulation`) - subcomponent_of_broader_mechanism: The spectral loss is a standard, application-specific training technique rather than a foundational concept, and fits within existing broader concepts of spectral-domain regularization.

## Links

- [Abstract](https://arxiv.org/abs/2605.14606)
- [PDF](https://arxiv.org/pdf/2605.14606)

