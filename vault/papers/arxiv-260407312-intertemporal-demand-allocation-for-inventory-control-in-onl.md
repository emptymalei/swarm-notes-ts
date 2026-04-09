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
processed_at: "2026-04-09T04:52:49Z"
created_at: "2026-04-09T04:52:49Z"
---

# Intertemporal Demand Allocation for Inventory Control in Online Marketplaces

**Authors**: Rene Caldentey, Tong Xie
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07312](https://arxiv.org/abs/2604.07312)

## Summary

This paper explores how online marketplaces can influence seller inventory strategies by strategically allocating order demand over time. By adjusting the predictability of individual seller sales streams, the platform directly impacts the sellers' safety-stock needs and their adoption of platform-managed fulfillment services. The authors demonstrate that the platform can control these inventory outcomes through non-discriminatory, low-memory routing policies that intentionally obfuscate aggregate demand signals from sellers.

## Key Contributions

- Develops a theoretical framework for intertemporal demand allocation as a mechanism to influence seller inventory replenishment policies in online marketplaces.
- Identifies that a platform can modulate seller safety-stock requirements by adjusting the predictability of their individual sales streams, independent of total demand share.
- Proves that uniform order splitting minimizes seller forecast uncertainty, whereas specific low-memory allocation rules can increase uncertainty to manage fulfillment adoption trade-offs.

## Open Questions & Future Work

- [[neutrality-constraints-platform-design]]
- [[dynamic-marketplace-governance-extensions]]

## Archivist Review

This paper proposes a theoretical framework for demand-routing-as-a-control-mechanism. While highly insightful, the primary contributions are formulated as theoretical proofs rather than reusable algorithmic concepts, and therefore no new concepts are added. The open questions regarding neutrality constraints and marketplace governance are approved as they address fundamental, unresolved challenges in platform operations and algorithmic policy.

### Approved Open Questions
- Neutrality constraints in platform design: This question is critical because neutrality constraints are often loosely defined in policy and regulatory contexts; understanding how different rigorous formulations constrain operational levers is essential for platform design and competition policy.
- Dynamic marketplace governance extensions: Extending this framework to non-stationary and strategic environments is necessary to translate these theoretical insights into practical, robust operational strategies for real-world digital marketplaces.

## Links

- [Abstract](https://arxiv.org/abs/2604.07312)
- [PDF](https://arxiv.org/pdf/2604.07312)

