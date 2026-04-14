---
# CSL-compatible fields
title: "PEMANT: Persona-Enriched Multi-Agent Negotiation for Travel"
author:
  - literal: "Yuran Sun"
  - literal: "Mustafa Sameen"
  - literal: "Yaotian Zhang"
  - literal: "Chia-yu Wu"
  - literal: "Xilei Zhao"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10475"

# Custom fields
paper_id: "2604.10475"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "household-aware-chain-of-planned-behavior-ha-copb"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:05:43Z"
created_at: "2026-04-14T05:05:43Z"
---

# PEMANT: Persona-Enriched Multi-Agent Negotiation for Travel

**Authors**: Yuran Sun, Mustafa Sameen, Yaotian Zhang, Chia-yu Wu, Xilei Zhao
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10475](https://arxiv.org/abs/2604.10475)

## Summary

PEMANT is a novel LLM-based multi-agent framework designed to model household-level trip generation by incorporating behavioral theory and intra-household interaction dynamics. The framework utilizes the Household-Aware Chain-of-Planned-Behavior (HA-CoPB) to transform demographic data into psychologically-rich persona profiles. These personas interact through a structured two-phase negotiation process to achieve realistic collective travel planning, consistently outperforming existing travel demand forecasting baselines on household travel survey datasets.

## Key Contributions

- Proposes PEMANT, a multi-agent LLM framework that integrates behavioral theory to simulate household-level trip generation.
- Introduces the HA-CoPB framework to convert static socio-demographic data into behaviorally-informed narrative profiles.
- Demonstrates state-of-the-art performance on national and regional household travel surveys compared to baseline models.

## Open Questions & Future Work

- [[llm-emergency-mobility-simulation-generalization]]

## Key Concepts

- [[household-aware-chain-of-planned-behavior-ha-copb]]: A theory-grounded framework that converts demographic data into narrative-based persona profiles reflecting behavioral drivers like attitudes and subjective norms.

## Archivist Review

I approved the Household-Aware Chain-of-Planned-Behavior framework as a novel, reusable methodology for integrating psychological theory into agent-based modeling. I also approved the open question regarding the generalization of these frameworks to extreme conditions, as it captures a fundamental limitation in current LLM-driven urban simulation. I rejected the name "PEMANT" itself as it is a specific system implementation rather than a generalizable concept.

### Approved Concepts
- Household-Aware Chain-of-Planned-Behavior (HA-CoPB): This framework bridges behavioral psychological theory with LLM-based agent profile generation for collective decision-making modeling.

### Approved Open Questions
- LLM Emergency Mobility Generalization: This tests the robustness and scalability of LLM-based behavioral simulation beyond stable, routine datasets, which is critical for life-critical urban systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.10475)
- [PDF](https://arxiv.org/pdf/2604.10475)

