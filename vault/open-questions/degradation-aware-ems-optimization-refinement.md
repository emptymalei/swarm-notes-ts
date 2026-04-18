---
created_at: '2026-04-18T04:51:53Z'
source_papers:
- '[[arxiv-260414994-degradation-aware-predictive-energy-management-for-fuel-cell]]'
title: Refining Degradation-Aware Energy Management
---

**Background:** Fuel cell-battery hybrid power systems in maritime vessels require energy management strategies that balance hydrogen fuel consumption against the long-term cost of fuel cell stack degradation. Existing strategies often struggle to integrate degradation-aware optimization within predictive control frameworks, particularly when operational data is limited.

**Question / Future Work:** Future research is needed to refine degradation modeling for fuel cell systems—moving beyond static threshold assumptions—and to explore the potential for hierarchical, multi-horizon control approaches where an overarching mission-scale optimization provides target states for the inner-loop predictive controller.

**Why It Matters:** These improvements are critical for enhancing the economic viability and operational life of fuel cell-based maritime power systems by more accurately reflecting the physical and economic reality of component aging.

**Evidence:** the fixed 10% performance drop for EOL definition of FCs is to be questioned for this application and instead be replaced by an optimization variable... As a next step, it will be interesting to determine whether a multi-horizon approach with an outer mission-scale optimization will allow for an improved performance.