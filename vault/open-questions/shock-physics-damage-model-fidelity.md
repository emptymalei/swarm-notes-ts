---
created_at: '2026-04-22T05:04:49Z'
source_papers:
- '[[arxiv-260418828-the-high-explosives-and-affected-targets-heat-dataset]]'
title: Shock Physics Damage Model Fidelity
---

**Background:** Eulerian computational fluid dynamics simulations of high-speed material deformation often rely on simplified constitutive models that exclude fracture and spallation phenomena.

**Question / Future Work:** The integration of explicit damage, fracture, and spallation models into surrogate training data is necessary for accurately predicting material survivability under extreme shock loading. Current benchmarks often overlook these failure modes, leading to systematic over-prediction of structural integrity.

**Why It Matters:** This gap prevents the development of predictive surrogates that can handle real-world material destruction and energy dissipation in high-velocity dynamics.

**Evidence:** The simulated solids can only deform elastically and plastically and never break, crack, or spall... Therefore, the solid dynamics captured in HEAT over-predict load-carrying capacity and survivability.