---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Long Term Pediatric Vaccine Tender Scheduling with Quantity Discounts"
description: "This paper extends the Hypothetically Coordinated Vaccine Market (HCVM) framework to address long-term pediatric vaccine procurement for low- and lower-middle-income countries through multi-year tender scheduling. The authors model multi-year tenders with flexible lengths and all-unit quantity discounts, comparing three distinct optimization objectives: balanced coordination, social-benefit maximization (minimizing missed doses), and producer profit maximization. Evaluation using UNICEF ten-year demand forecasts reveals that the chosen procurement objective is the primary driver of cost and schedule complexity, rather than demand variability. Furthermore, the findings highlight that while quantity discounts can reduce costs, they risk market concentration and supply chain vulnerability, particularly for mature vaccine markets."
resource: "https://arxiv.org/abs/2610.19045"
tags:
  - "supply-chain-optimization"
  - "logistics"
  - "healthcare"
  - "stochastic-modeling"
  - "decision-making"
  - "forecasting"
  - "multi-objective-optimization"
  - "risk-management"
timestamp: "2026-10-18T00:49:54Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Nicholas Uhorchak"
  - literal: "Ruben Proano"
  - literal: "Sandra Eksioglu"
  - literal: "Burak Eksioglu"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.19045"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "mitigating-procurement-concentration-risks"
    description: "How can procurement mechanisms be designed to leverage the cost benefits of quantity discounts without compromising market resilience and producer diversity?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:49:54Z"
created_at: "2026-10-18T00:49:54Z"
---

# Long Term Pediatric Vaccine Tender Scheduling with Quantity Discounts

**Authors**: Nicholas Uhorchak, Ruben Proano, Sandra Eksioglu, Burak Eksioglu
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.19045](https://arxiv.org/abs/2610.19045)

## Summary

This paper extends the Hypothetically Coordinated Vaccine Market (HCVM) framework to address long-term pediatric vaccine procurement for low- and lower-middle-income countries through multi-year tender scheduling. The authors model multi-year tenders with flexible lengths and all-unit quantity discounts, comparing three distinct optimization objectives: balanced coordination, social-benefit maximization (minimizing missed doses), and producer profit maximization. Evaluation using UNICEF ten-year demand forecasts reveals that the chosen procurement objective is the primary driver of cost and schedule complexity, rather than demand variability. Furthermore, the findings highlight that while quantity discounts can reduce costs, they risk market concentration and supply chain vulnerability, particularly for mature vaccine markets.

## Key Contributions

- Extended the Hypothetically Coordinated Vaccine Market (HCVM) framework to support multi-year tender scheduling with flexible durations and all-unit quantity discounts.
- Demonstrated through simulation that procurement objectives (social benefit vs. producer profit), rather than demand uncertainty, are the primary drivers of tender cost and schedule complexity.
- Identified that quantity discounts significantly increase market concentration among large producers, thereby heightening supply chain vulnerability in low-income markets.
- Determined that the effectiveness of price discounts is dictated by market maturity rather than vaccine valency, with monovalent rotavirus vaccines responding well while HPV and PCV remain uncompetitive.

## Limitations

The study focuses on LIC and LMIC contexts and specific vaccine categories, which may not directly generalize to high-income markets with different regulatory and insurance structures.

## Open Questions & Future Work

- [[mitigating-procurement-concentration-risks]]

## Archivist Review

The paper applies optimization and simulation to vaccine procurement markets. While it provides valuable insights for global health logistics, most candidates are too domain-specific or represent standard economic concepts. The open question regarding market concentration risks in procurement is approved as it addresses a fundamental challenge in mechanism design and robust supply chain optimization.

### Approved Open Questions
- Mitigating Procurement-Induced Market Concentration: Market concentration leads to supply chain vulnerability; finding a balance is essential for long-term global supply chain security and resilient mechanism design.

### Rejected Candidates
- [concept] HCVM Framework (`hcvm-framework`) - paper_local: The Hypothetically Coordinated Vaccine Market framework is a specialized modeling approach specific to vaccine procurement rather than a general-purpose ML or optimization methodology.
- [dataset] unicef-vaccine-demand-forecasts (`unicef-vaccine-demand-forecasts`) - not_reusable: This is a data source and set of forecasts used for simulation rather than a standardized, named benchmark dataset for the research community.
- [open_question] Economic Strategies for High-Cost Vaccine Access (`high-cost-vaccine-access-models`) - other: This is primarily a policy and subsidy design question rather than a technical bottleneck in optimization or machine learning.
- [concept] Quantity Discounts (`quantity-discounts`) - not_novel: Quantity discounts are a standard economic mechanism and not a novel methodology introduced by this paper.
- [concept] Tender Scheduling (`tender-scheduling`) - generic: Tender scheduling is a standard operational research problem category rather than a specific reusable algorithmic innovation.

## Links

- [Abstract](https://arxiv.org/abs/2610.19045)
- [PDF](https://arxiv.org/pdf/2610.19045)

