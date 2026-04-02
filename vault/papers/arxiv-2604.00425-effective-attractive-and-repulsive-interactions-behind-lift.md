---
# CSL-compatible fields
title: "Effective attractive and repulsive interactions behind lift synchronization"
author:
  - literal: "Mitsusuke Tarama"
  - literal: "Sakurako Tanida"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00425"

# Custom fields
paper_id: "2604.00425"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "effective-interaction-decomposition-synchronization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:38:31Z"
created_at: "2026-04-02T05:38:31Z"
---

# Effective attractive and repulsive interactions behind lift synchronization

**Authors**: Mitsusuke Tarama, Sakurako Tanida
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00425](https://arxiv.org/abs/2604.00425)

## Summary

This paper investigates the underlying mechanisms of lift synchronization by analyzing time-series data from a stochastic rule-based discrete model. The authors reveal that the effective interaction between lifts is characterized by both attractive and repulsive forces. By manipulating model parameters, they demonstrate the ability to control synchronization states, specifically enabling transitions between in-phase and anti-phase modes, offering a pathway for optimizing real-world transport systems.

## Key Contributions

- Demonstrates that lift synchronization is governed by a balance of competing effective attractive and repulsive forces between units.
- Proposes a strategy to control lift dynamics by tuning the ratio of these interactions, facilitating transitions between in-phase and anti-phase synchronization states.
- Validates the mechanism using a stochastic rule-based discrete lift model, providing a quantitative basis for future optimization of real-world lift systems.

## Open Questions & Future Work

- [[synchronization-efficiency-tradeoff-transportation]]

## Key Concepts

- [[effective-interaction-decomposition-synchronization]]: A framework for modeling synchronization in collective systems by decomposing inter-agent dynamics into competing attractive and repulsive components.

## Archivist Review

The paper provides a unique perspective on modeling synchronization in stochastic agent-based systems. I approved the concept of effective interaction decomposition as it is highly reusable for researchers studying collective dynamics in other domains (like traffic or logistics). The open question was reframed to explicitly focus on the trade-off between synchronization states and operational efficiency, which is a known gap in control theory for human-centric transport.

### Approved Concepts
- Effective interaction decomposition for multi-agent synchronization: It provides a formal mechanism for analyzing and tuning synchronization behaviors in collective, rule-based systems beyond simple heuristic control.

### Approved Open Questions
- Efficiency impact of lift synchronization: Determining if synchronization is a symptom of inefficiency or a desirable state for throughput is critical for deploying adaptive control in high-density urban infrastructure.

### Rejected Candidates
- [concept] Effective interaction decomposition in lift systems (`effective-interaction-decomposition-lift-systems`) - other: Renamed to be more general and applicable to future multi-agent synchronization research beyond just lift systems.
- [open_question] Efficiency impact of lift synchronization (`lift-synchronization-efficiency-impact`) - other: Renamed for greater thematic clarity regarding the trade-offs between coordination and throughput.

## Links

- [Abstract](https://arxiv.org/abs/2604.00425)
- [PDF](https://arxiv.org/pdf/2604.00425)

