---
created_at: '2026-04-09T04:52:49Z'
modified_at: '2026-04-10T15:31:07Z'
source_papers:
- '[[arxiv-260407312-intertemporal-demand-allocation-for-inventory-control-in-onl]]'
title: Broadening Neutrality in Platform Design
---

**Background:** Digital platforms that function as market makers frequently exert control over order routing, affecting seller-level inventory through the informational properties of demand streams. This mechanism is particularly significant when platforms also offer fulfillment services, which give the platform an economic stake in seller inventory despite decentralized decision-making.

**Question / Future Work:** The authors identify that neutrality constraints—requiring platforms to treat sellers symmetrically in expectation regarding mean demand and forecast risk—limit but do not eliminate the platform's ability to influence seller-level inventory. It remains an open question how alternative definitions of neutrality, such as those encompassing multi-step forecast errors, entire second-order spectral structures, or specific exposure/share floors, affect the implementable range of inventory outcomes and optimal platform design.

**Why It Matters:** This question is critical because neutrality constraints are often loosely defined in policy and regulatory contexts; understanding how different rigorous formulations constrain operational levers is essential for platform design and competition policy.

**Evidence:** Beyond equal mean shares and equal one-step-ahead MSFE, one could require neutrality over longer horizons (multi-step forecast errors), preserve the entire second-order structure (e.g., identical autocovariance or spectral densities), or impose exposure/share floors motivated by fairness regulation; characterizing the implementable set and the platform’s optimal design under such alternative constraints is an important next step.