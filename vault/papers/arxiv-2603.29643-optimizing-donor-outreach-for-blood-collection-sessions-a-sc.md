---
# CSL-compatible fields
title: "Optimizing Donor Outreach for Blood Collection Sessions: A Scalable Decision Support Framework"
author:
  - literal: "André Carneiro"
  - literal: "Pedro T. Monteiro"
  - literal: "Rui Henriques"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29643"

# Custom fields
paper_id: "2603.29643"
paper_source: "arxiv"
domain: "operations-research"
tags:
  - "optimization"
  - "decision-support"
  - "logistics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "constraint-aware-invitation-scheduling"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:40:17Z"
created_at: "2026-04-02T05:40:17Z"
---

# Optimizing Donor Outreach for Blood Collection Sessions: A Scalable Decision Support Framework

**Authors**: André Carneiro, Pedro T. Monteiro, Rui Henriques
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29643](https://arxiv.org/abs/2603.29643)

## Summary

This paper proposes a scalable decision support framework for optimizing blood donor invitations to manage supply while mitigating donor fatigue. The authors evaluate a binary integer linear programming (BILP) formulation and a computationally efficient greedy heuristic, both incorporating realistic constraints like blood-type demand, geographic proximity, and donor safety. Using real-world data from the Lisbon region, the study demonstrates that the greedy heuristic offers a practical, high-performance alternative to global BILP optimization for operational planning. The framework provides a robust tool for health authorities to improve recruitment efficiency while minimizing adverse donor impacts.

## Key Contributions

- Introduces a novel optimization framework for donor invitation scheduling that accounts for blood-type demand targets, donor eligibility, and travel distance.
- Provides a comparative analysis of a binary integer linear programming (BILP) model versus a greedy heuristic, demonstrating significant gains in computational efficiency (188x less memory, 115x faster runtime) with only minor trade-offs in demand fulfillment (3.9 pp).
- Integrates a prospective pipeline covering organic attendance forecasting, quantile-based demand targets, and residual capacity estimation to effectively bridge supply-demand gaps in blood donation networks.

## Open Questions & Future Work

- [[empirically-calibrating-participation-response-probabilities]]

## Key Concepts

- [[constraint-aware-invitation-scheduling]]: An optimization framework for scheduling participant invitations that accounts for individual eligibility, resource demand, and accessibility constraints to balance supply and participant burden.

## Archivist Review

I approved the concept of 'Constraint-Aware Invitation Scheduling' as a reusable pattern for multi-objective resource allocation in logistics. I also approved a broader research question regarding empirical calibration of participant-response probabilities, as this is a fundamental bottleneck for optimization frameworks that rely on stochastic attendance. I rejected the geolocation question as it pertains more to data cleaning and fidelity than to an architectural research problem.

### Approved Concepts
- Constraint-Aware Invitation Scheduling: Provides a generalized optimization pattern for managing participant fatigue and supply constraints in invitation-based logistics.

### Approved Open Questions
- Empirical calibration of participation-response probabilities: This is a core bottleneck for matching logistical supply to capacity; inaccurate probabilities lead to either systematic resource wastage or significant gaps in demand fulfillment.

### Rejected Candidates
- [open_question] Calibrate invitation attendance probabilities (`calibrate-invitation-attendance-probabilities`) - duplicate_existing: Replaced by a broader, more formally scoped question focusing on participation-response dynamics.
- [open_question] Ground-truth geolocation validation (`ground-truth-geolocation-validation`) - low_impact: This is a routine data quality issue rather than a foundational research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2603.29643)
- [PDF](https://arxiv.org/pdf/2603.29643)

