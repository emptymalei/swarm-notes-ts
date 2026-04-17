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
domain: "energy-systems"
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
processed_at: "2026-04-17T05:06:37Z"
created_at: "2026-04-17T05:06:37Z"
---

# AC-OPF Feasibility Analysis and Sensitivity-Guided Capacitor Placement in a High-PV Islanded Microgrid

**Authors**: Aaron Jones, Marija Ilic
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14372](https://arxiv.org/abs/2604.14372)

## Summary

This paper evaluates AC Optimal Power Flow strategies in a high-PV islanded microgrid using a digital twin to assess economic and reliability trade-offs over a 47-hour horizon. The authors propose a sensitivity-guided approach for capacitor placement, utilizing composite optimization sensitivity metrics to identify optimal grid upgrade locations. By balancing infrastructure costs against avoided load-shedding penalties, the framework provides a decision-support tool for grid reliability improvements in distributed energy environments.

## Key Contributions

- Conducts a comparative AC-OPF analysis on a city-scale islanded microgrid with high PV penetration across four distinct objective functions.
- Introduces a sensitivity-guided capacitor placement methodology using composite OSQ and OSV scores derived from multi-objective OPF optimization.
- Develops a post-processing planning framework that balances shunt capacitor upgrade costs against the economic value of avoided load shedding.

## Open Questions & Future Work

- [[integrating-battery-storage-in-microgrid-planning]]

## Archivist Review

The paper proposes a power-system specific methodology for grid infrastructure investment. While valuable for grid planning, the sensitivity-guided placement method and its associated metrics do not represent generalizable ML forecasting concepts. The open question regarding battery storage integration was approved as it reflects a foundational challenge in balancing flexible assets with fixed infrastructure in autonomous energy systems.

### Approved Open Questions
- Integrating Battery Storage in Microgrid Planning: Battery storage is a critical, increasingly common asset in microgrids that can provide both active and reactive power support; integrating it is essential for realistic, modern microgrid planning and economic trade-off analysis.

### Rejected Candidates
- [concept] Sensitivity-Guided Capacitor Placement (`sensitivity-guided-capacitor-placement`) - not_reusable: The methodology is specific to AC-OPF microgrid infrastructure planning and is not sufficiently generalizable to broader ML or time-series forecasting paradigms.
- [concept] Composite Optimization Sensitivity Score (`composite-optimization-sensitivity-score`) - subcomponent_of_broader_mechanism: This is a local scoring mechanism for a specific power flow optimization problem rather than a reusable ML concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.14372)
- [PDF](https://arxiv.org/pdf/2604.14372)

