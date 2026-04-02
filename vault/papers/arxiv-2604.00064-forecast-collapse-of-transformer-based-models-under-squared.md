---
# CSL-compatible fields
title: "Forecast collapse of transformer-based models under squared loss in financial time series"
author:
  - literal: "Pierre Andreoletti"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2604.00064"

# Custom fields
paper_id: "2604.00064"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:40:30Z"
created_at: "2026-04-02T05:40:30Z"
---

# Forecast collapse of transformer-based models under squared loss in financial time series

**Authors**: Pierre Andreoletti
**Date**: 2026-03-31
**Paper ID**: [arxiv:2604.00064](https://arxiv.org/abs/2604.00064)

## Summary

This paper analyzes the performance degradation of highly expressive models like Transformers when applied to financial time series under squared loss. The author identifies a theoretical regime where conditional expectations are degenerate, causing complex models to generate spurious fluctuations that increase prediction variance without reducing bias. Experimental results on EUR/USD exchange rate data confirm that these models often underperform simple linear baselines, supporting the conclusion that model expressivity is counterproductive in the presence of weak conditional structure.

## Key Contributions

- Identifies a theoretical 'forecast collapse' phenomenon where highly expressive models like Transformers fail under squared loss in weak conditional structures.
- Demonstrates that in regimes with degenerate conditional expectations, increased model expressivity amplifies prediction variance via spurious trajectory fluctuations without bias reduction.
- Provides empirical validation on high-frequency EUR/USD data, showing Transformers underperform simple linear benchmarks due to this variance-driven degradation.

## Links

- [Abstract](https://arxiv.org/abs/2604.00064)
- [PDF](https://arxiv.org/pdf/2604.00064)

