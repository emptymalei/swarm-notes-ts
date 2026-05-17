---
# CSL-compatible fields
title: "MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting"
author:
  - literal: "Chunlei Shi"
  - literal: "Cui Wu"
  - literal: "Xiang Xu"
  - literal: "Hao Li"
  - literal: "Ni Fan"
  - literal: "Xue Han"
  - literal: "Yongchao Feng"
  - literal: "Yufeng Zhu"
  - literal: "Boyu Liu"
  - literal: "Zengliang Zang"
  - literal: "Hongbin Wang"
  - literal: "Yanlan Yang"
  - literal: "Dan Niu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14606"

# Custom fields
paper_id: "2605.14606"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "mambarain"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:03Z"
created_at: "2026-05-17T05:24:03Z"
---

# MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting

**Authors**: Chunlei Shi, Cui Wu, Xiang Xu, Hao Li, Ni Fan, Xue Han, Yongchao Feng, Yufeng Zhu, Boyu Liu, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14606](https://arxiv.org/abs/2605.14606)

## Summary

MambaRain is a novel multi-scale encoder-decoder framework designed to enhance 0-3 hour precipitation nowcasting by integrating Mamba's selective state space models with spatial self-attention. While Mamba captures long-range temporal dynamics with linear complexity, the added self-attention modules explicitly model spatial correlations, overcoming limitations in traditional sequential modeling. Additionally, the framework employs a spectral loss function to preserve fine-scale motion details and mitigate common blurring issues in precipitation forecasting. Experimental results confirm that this approach extends reliable forecasting horizons beyond the typical 90-minute limit.

## Key Contributions

- Introduced MambaRain, a hybrid architecture combining Mamba and self-attention, extending precipitation forecasting horizons to 0-3 hours.
- Demonstrated that the synergy of Mamba's linear-complexity temporal modeling and self-attention's spatial correlation capture significantly reduces performance degradation beyond 90 minutes.
- Proposed a spectral loss formulation to address blurring artifacts in precipitation fields, preserving fine-scale motion details.

## Open Questions & Future Work

- [[deterministic-nowcasting-uncertainty-blurring]]

## Key Concepts

- [[mambarain]]: A multi-scale encoder-decoder architecture that integrates Mamba's temporal modeling with self-attention for spatiotemporal precipitation forecasting.

## Archivist Review

I have approved MambaRain as a representative hybrid architecture for long-range spatiotemporal forecasting. I have also approved the open question regarding the trade-off between deterministic blurring and uncertainty quantification, as it highlights a fundamental limitation in operational meteorological forecasting. No datasets were approved as none were explicitly provided or sufficiently described as reusable benchmarks.

### Approved Concepts
- MambaRain: It establishes a novel hybrid architecture specifically designed for long-range precipitation nowcasting by combining State Space Models and self-attention.

### Approved Open Questions
- Deterministic Nowcasting and Uncertainty: Determining how to achieve high-resolution, sharp predictions while quantifying uncertainty is essential for moving beyond deterministic limitations in operational meteorological applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.14606)
- [PDF](https://arxiv.org/pdf/2605.14606)

