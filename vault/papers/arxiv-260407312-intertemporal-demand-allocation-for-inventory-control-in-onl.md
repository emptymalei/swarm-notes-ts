---
# CSL-compatible fields
title: "Intertemporal Demand Allocation for Inventory Control in Online Marketplaces"
author:
  - literal: "Rene Caldentey"
  - literal: "Tong Xie"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07312"

# Custom fields
paper_id: "2604.07312"
paper_source: "arxiv"
domain: "nlp"
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
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:48:00Z"
created_at: "2026-04-11T04:48:00Z"
---

# Intertemporal Demand Allocation for Inventory Control in Online Marketplaces

**Authors**: Rene Caldentey, Tong Xie
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07312](https://arxiv.org/abs/2604.07312)

## Summary

This paper explores how online platforms can strategically allocate orders across sellers to influence their fulfillment choices and inventory levels. By manipulating the predictability of seller sales streams, the platform controls the perceived need for safety stock, effectively nudging sellers toward platform-provided fulfillment services. The analysis reveals a fundamental trade-off between the adoption of platform fulfillment and the aggregate inventory levels maintained by sellers, identifying demand allocation as a key design lever for marketplace operations.

## Key Contributions

- Develops a model to influence seller inventory choices in online marketplaces via strategic intertemporal demand allocation.
- Demonstrates that demand allocation modulates sellers' safety-stock requirements by altering the predictability of their individual sales streams.
- Proves that uniform order splitting minimizes forecast uncertainty, while higher uncertainty levels can be implemented through low-memory allocation rules that obscure aggregate demand signals.

## Open Questions & Future Work

- [[defining-platform-neutrality-constraints]]
- [[extending-allocation-nonstationary-demand]]

## Archivist Review

I reviewed the submission and found that while the economic model is elegant, it primarily describes an application-specific optimization framework rather than offering a generalizable ML concept. The concepts provided in the submission were either too specific to the marketplace inventory application or represent generic operational concepts. I have approved the two open questions as they represent significant, reusable research gaps in the intersection of demand allocation, marketplace governance, and non-stationary time-series forecasting.

### Approved Open Questions
- Defining platform neutrality constraints: Defining neutrality is a foundational component of marketplace governance, and varying the definition changes the feasible space for platform optimization. Expanding these definitions is critical for applying the model to practical, regulated marketplace environments.
- Extending allocation to non-stationary demand: Real-world demand is rarely stationary, and allocation policies that fail to account for time-varying patterns may be sub-optimal or fail to provide the intended inventory-shaping effects.

## Links

- [Abstract](https://arxiv.org/abs/2604.07312)
- [PDF](https://arxiv.org/pdf/2604.07312)

