---
# CSL-compatible fields
title: "AC-OPF Feasibility Analysis and Sensitivity-Guided Capacitor Placement in a High-PV Islanded Microgrid"
author:
  - literal: "Aaron Jones"
  - literal: "Marija Ilic"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14372"

# Custom fields
paper_id: "2604.14372"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "optimization-sensitivity-composite-score-oscs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:53:14Z"
created_at: "2026-04-18T04:53:14Z"
---

# AC-OPF Feasibility Analysis and Sensitivity-Guided Capacitor Placement in a High-PV Islanded Microgrid

**Authors**: Aaron Jones, Marija Ilic
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14372](https://arxiv.org/abs/2604.14372)

## Summary

This paper presents a comparative AC-OPF analysis for a high-PV islanded microgrid using a digital twin, evaluating economic and reliability-driven dispatch strategies over a 47-hour time horizon. The authors introduce a sensitivity-guided approach that uses optimization-derived metrics to rank candidate buses for shunt capacitor upgrades. By balancing infrastructure costs against the value-of-lost-load, the method provides a rigorous framework for reactive power planning and load shedding mitigation. Results confirm that the proposed placement strategy restores service continuity while maintaining economic viability in solar-heavy microgrid environments.

## Key Contributions

- Introduces a sensitivity-guided methodology combining reactive power (OSQ) and voltage (OSV) sensitivities to rank optimal locations for shunt capacitor placement.
- Develops a post-processing planning optimization that quantifies trade-offs between capacitor installation costs and avoided value-of-lost-load.
- Demonstrates that the proposed framework achieves 100% load service in a high-PV islanded microgrid, effectively balancing reactive power management with economic dispatch.

## Open Questions & Future Work

- [[battery-storage-reactive-support-microgrids]]

## Key Concepts

- [[optimization-sensitivity-composite-score-oscs]]: A methodology for infrastructure ranking that aggregates multiple optimization-derived sensitivity metrics (e.g., reactive power and voltage sensitivities) into a unified placement score.

## Archivist Review

I have approved the composite sensitivity metric as it represents a reusable approach to infrastructure planning in constrained networks, and the open question regarding BESS integration as it captures a critical bottleneck for future power systems research. Other candidates were not submitted, so the review focused on these core contributions.

### Approved Concepts
- Optimization Sensitivity Composite Score (OSCS): Central to the paper's novel methodology for reactive power planning in power systems.

### Approved Open Questions
- Battery storage for reactive support: Expanding reactive support infrastructure beyond passive capacitors to include active storage systems is essential for improving the hosting capacity and operational flexibility of islanded microgrids.

## Links

- [Abstract](https://arxiv.org/abs/2604.14372)
- [PDF](https://arxiv.org/pdf/2604.14372)

