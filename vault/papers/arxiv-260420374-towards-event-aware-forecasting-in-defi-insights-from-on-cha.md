---
# CSL-compatible fields
title: "Towards Event-Aware Forecasting in DeFi: Insights from On-chain Automated Market Maker Protocols"
author:
  - literal: "Huaiyu Jia"
  - literal: "Jiehshun You"
  - literal: "Yizhi Luo"
  - literal: "Jingyu Liu"
  - literal: "Shuo Sun"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20374"

# Custom fields
paper_id: "2604.20374"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "uncertainty-weighted-mean-squared-error-uwm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:07:03Z"
created_at: "2026-04-23T05:07:03Z"
---

# Towards Event-Aware Forecasting in DeFi: Insights from On-chain Automated Market Maker Protocols

**Authors**: Huaiyu Jia, Jiehshun You, Yizhi Luo, Jingyu Liu, Shuo Sun
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20374](https://arxiv.org/abs/2604.20374)

## Summary

This paper addresses the limitations of current forecasting models in DeFi, which often overlook the event-driven micro-structural dynamics of Automated Market Makers (AMMs). The authors introduce a new dataset of 8.9 million on-chain events and propose an Uncertainty Weighted Mean Squared Error (UWM) loss function to better integrate block interval regression with Time-Point Process (TPP) modeling. Experimental results across eight TPP architectures demonstrate that UWM significantly reduces time prediction errors while maintaining classification accuracy, providing a robust new benchmark for on-chain event forecasting.

## Key Contributions

- Constructed a dataset of 8.9 million on-chain event records across four major DeFi protocols (Pendle, Uniswap v3, Aave, Morpho) for fine-grained event analysis.
- Proposed the Uncertainty Weighted Mean Squared Error (UWM) loss function, which improves time prediction error by 56.41% over standard TPP objectives.
- Established a benchmark for event-aware predictive modeling in DeFi, providing a new methodological framework for handling discrete, event-driven on-chain price discovery.

## Open Questions & Future Work

- [[defi-event-aware-forecasting-microstructure]]

## Key Concepts

- [[uncertainty-weighted-mean-squared-error-uwm]]: A loss function for event-aware forecasting that integrates block interval regression into TPP objectives by weighting uncertainty with homoscedasticity.

## Archivist Review

I have approved the Uncertainty Weighted Mean Squared Error (UWM) loss as a reusable mechanism for event-aware time-series forecasting. The open question regarding DeFi micro-structure forecasting is approved because it articulates a specific, non-trivial gap in modeling bursty event-driven systems. I rejected the individual protocol datasets as they are sub-parts of the aggregate event dataset provided in the paper and are too domain-specific for a general-purpose ML vault.

### Approved Concepts
- Uncertainty Weighted Mean Squared Error (UWM): The loss function specifically addresses the dual challenge of event timing and classification in event-driven financial systems, bridging the gap between point process modeling and regression-based interval prediction.

### Approved Open Questions
- DeFi Event-Aware Forecasting Microstructure: This is critical for advancing automated yield speculation, portfolio rebalancing, and real-time arbitrage execution in DeFi, where timing and type accuracy are essential.

### Rejected Candidates
- [dataset] Pendle (`pendle`) - low_impact: Protocol-specific subsets are too granular and non-reusable as standalone dataset entries.
- [dataset] Uniswap v3 (`uniswap-v3`) - low_impact: Protocol-specific subsets are too granular and non-reusable as standalone dataset entries.
- [dataset] Aave (`aave`) - low_impact: Protocol-specific subsets are too granular and non-reusable as standalone dataset entries.
- [dataset] Morpho (`morpho`) - low_impact: Protocol-specific subsets are too granular and non-reusable as standalone dataset entries.

## Links

- [Abstract](https://arxiv.org/abs/2604.20374)
- [PDF](https://arxiv.org/pdf/2604.20374)

