---
# CSL-compatible fields
title: "Dual-Temporal LSTM with Hybrid Attention for Airline Passenger Load Factor Forecasting: Integrating Intra-Flight and Inter-Flight Booking Dynamics"
author:
  - literal: "ASM Nazrul Islam"
  - literal: "Md. Hasanul Kabir"
  - literal: "Md. Liakot Ali"
  - literal: "Joydeb Kumar Sana"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11569"

# Custom fields
paper_id: "2605.11569"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dual-temporal-forecasting-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:25:21Z"
created_at: "2026-05-13T05:25:21Z"
---

# Dual-Temporal LSTM with Hybrid Attention for Airline Passenger Load Factor Forecasting: Integrating Intra-Flight and Inter-Flight Booking Dynamics

**Authors**: ASM Nazrul Islam, Md. Hasanul Kabir, Md. Liakot Ali, Joydeb Kumar Sana
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11569](https://arxiv.org/abs/2605.11569)

## Summary

This paper addresses the limitations of unidimensional airline demand forecasting by introducing a dual-stream LSTM model that captures both intra-flight booking accumulation and inter-flight historical patterns. The architecture utilizes hybrid attention, concatenation, and gated fusion to synthesize these complementary temporal dimensions. Empirical results on Biman Bangladesh Airlines data show that the model outperforms traditional benchmarks and provides robust performance across diverse flight categories, leading to its direct integration into operational workflows.

## Key Contributions

- Proposes a Dual-Temporal LSTM with Hybrid Attention that simultaneously models intra-flight accumulation and inter-flight booking trends to enhance forecasting accuracy.
- Introduces a robust load factor forecasting approach that mitigates operational fragility caused by variations in aircraft capacity.
- Achieves a Mean Absolute Error of 2.8167 and R2 of 0.9495 on real-world airline reservation data, demonstrating superior performance over tree-based and single-stream benchmarks.

## Open Questions & Future Work

- [[cabin-class-level-demand-disaggregation]]

## Key Concepts

- [[dual-temporal-forecasting-framework]]: A time-series forecasting architecture that fuses horizontal (intra-event progression) and vertical (inter-event historical cycle) temporal input streams.

## Archivist Review

I approved the 'Dual-Temporal Forecasting Framework' as a reusable architecture for handling two-dimensional time-series data (progression vs. cycle). I also approved 'Cabin Class Demand Disaggregation' as a significant, unresolved challenge in industrial demand forecasting. I rejected the author-provided candidate for the concept because it was too implementation-specific, favoring the broader framework term instead.

### Approved Concepts
- Dual-Temporal Forecasting Framework: This framework effectively solves the unidimensionality limitation in supply chain and demand forecasting by integrating orthogonal temporal streams (e.g., progression vs. cycle).

### Approved Open Questions
- Cabin Class Demand Disaggregation: Class-specific modeling is critical for revenue management and optimizing seat inventory in multi-class cabin environments.

### Rejected Candidates
- [concept] Dual-Temporal LSTM with Hybrid Attention (`dual-temporal-lstm-with-hybrid-attention`) - subcomponent_of_broader_mechanism: The concept is overly specific to the LSTM implementation; the overarching structural idea (dual-stream temporal fusion) is captured better by the approved broader concept.
- [open_question] Cabin-Class-Specific PLF Forecasting (`cabin-class-level-plf-forecasting`) - duplicate_existing: Renamed to a more canonical open question slug for broader applicability in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.11569)
- [PDF](https://arxiv.org/pdf/2605.11569)

