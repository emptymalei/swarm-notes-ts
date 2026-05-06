---
# CSL-compatible fields
title: "Online Energy Management for Bidirectional EV Charging with Rooftop PV: An Aging-Aware MPC Approach"
author:
  - literal: "Francesco Popolizio"
  - literal: "Albert Škegro"
  - literal: "Torsten Wik"
  - literal: "Chih Feng Lee"
  - literal: "Changfu Zou"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03844"

# Custom fields
paper_id: "2605.03844"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "transformer"
  - "model-predictive-control"
  - "energy-management"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-06T05:11:17Z"
created_at: "2026-05-06T05:11:17Z"
---

# Online Energy Management for Bidirectional EV Charging with Rooftop PV: An Aging-Aware MPC Approach

**Authors**: Francesco Popolizio, Albert Škegro, Torsten Wik, Chih Feng Lee, Changfu Zou
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03844](https://arxiv.org/abs/2605.03844)

## Summary

This paper presents an online, aging-aware energy management strategy for vehicle-to-grid (V2G) and vehicle-to-home (V2H) integration, utilizing model predictive control to optimize power flows while mitigating battery degradation. The system employs a Transformer-based forecaster to predict household load and solar irradiance, enabling effective energy arbitrage and solar self-consumption. Results indicate that the approach maximizes economic gains across diverse scenarios while maintaining user mobility requirements and minimizing long-term battery aging.

## Key Contributions

- Proposes an aging-aware model predictive control (MPC) framework for bi-directional EV charging (V2G/V2H) that incorporates comprehensive battery cycle and calendar degradation models.
- Integrates a Transformer-based forecaster to generate short-term household load and PV solar irradiance predictions for operational decision-making.
- Demonstrates that the strategy achieves up to EUR 2410.5 in annual economic gain compared to smart unidirectional charging with only 1.27% additional battery degradation over a one-year horizon.

## Open Questions & Future Work

- [[multi-user-network-aware-v2g-management]]

## Archivist Review

The paper proposes an application of well-known control techniques (MPC with penalty functions) to a specific domain (V2G/V2H energy management). The control framework itself is not a novel machine learning concept. The proposed open question is a significant research challenge that represents a clear, unresolved bottleneck for the scalability and real-world utility of V2G systems.

### Approved Open Questions
- Multi-user Network-aware V2G Management: Scaling from single-user to multi-user and network-aware settings is critical to understanding the aggregate feasibility of V2G technology for power grid support.

### Rejected Candidates
- [concept] Aging-aware Model Predictive Control (`aging-aware-model-predictive-control`) - not_novel: The combination of model predictive control with specific degradation costs is a well-established control engineering technique, not a novel ML concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.03844)
- [PDF](https://arxiv.org/pdf/2605.03844)

