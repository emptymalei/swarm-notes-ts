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
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:31:07Z"
created_at: "2026-04-10T15:31:07Z"
---

# Intertemporal Demand Allocation for Inventory Control in Online Marketplaces

**Authors**: Rene Caldentey, Tong Xie
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07312](https://arxiv.org/abs/2604.07312)

## Summary

This paper studies how online marketplaces can influence seller inventory and fulfillment choices by strategically allocating demand across sellers over time. By manipulating the predictability of individual seller sales streams, the platform effectively modulates safety-stock requirements for fulfill-by-merchant (FBM) versus fulfill-by-platform (FBP) models. The authors derive a class of nondiscriminatory allocation policies that trade off platform fulfillment adoption against inventory holding costs. Their work demonstrates that informational control through demand routing is a potent lever for operational design in digital marketplaces.

## Key Contributions

- Develops a framework for intertemporal demand allocation in online marketplaces to influence seller inventory replenishment behavior.
- Identifies that platform-controlled demand predictability serves as a key operational lever to manage seller safety-stock requirements and FBP adoption.
- Proves that uniform order splitting minimizes forecast uncertainty, while higher-uncertainty regimes require allocation rules that obscure aggregate demand signals from sellers.

## Open Questions & Future Work

- [[neutrality-constraints-platform-design]]
- [[non-stationary-demand-allocation]]

## Archivist Review

The paper proposes an interesting operational mechanism for influencing inventory via demand routing, but the core concepts are specific to marketplace economics and inventory theory rather than broadly reusable ML forecasting methods. I approved the neutrality constraint question as it addresses fundamental limitations of platform algorithm design, but rejected the non-stationary demand question as it is a duplicate of existing open questions regarding non-stationarity and regime shifts.

### Approved Open Questions
- Broadening Neutrality in Platform Design: This is technically important as it defines the boundary of the platform's design flexibility under increasingly common regulatory and reputational pressures regarding algorithmic fairness.
- Allocation Under Non-Stationary Demand: Real-world marketplace demand is rarely stationary; thus, this extension is critical for bridging the gap between theoretical models and operational practice in e-commerce.

### Rejected Candidates
- [open_question] Allocation Under Non-Stationary Demand (`non-stationary-demand-allocation`) - duplicate_existing: This is a duplicate entry; a similar question exists in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.07312)
- [PDF](https://arxiv.org/pdf/2604.07312)

