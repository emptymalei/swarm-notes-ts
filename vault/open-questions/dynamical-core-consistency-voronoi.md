---
created_at: '2026-04-09T04:54:12Z'
source_papers:
- '[[arxiv-260407103-a-new-high-order-finite-volume-advection-scheme-on-spherical]]'
title: Dynamical Core-Advection Consistency
---

**Background:** Current mimetic finite-volume schemes for the shallow-water equations on spherical Voronoi grids often face constraints from low-order dynamical core discretizations, which limit the accuracy achievable by high-order tracer advection schemes.

**Question / Future Work:** There is an unresolved need to improve the consistency between high-order tracer transport schemes and the underlying dynamical core discretizations (e.g., TRiSK) to mitigate grid-induced errors and grid imprinting in numerical weather models. Future efforts should focus on integrating these high-order fluxes into the momentum equations to achieve higher-order, consistent shallow-water solvers.

**Why It Matters:** Addressing this bottleneck is essential for advancing state-of-the-art atmospheric models (like MPAS/MONAN) and ensuring numerical consistency in global circulation simulations.

**Evidence:** One of our main findings is that grid imprinting is still observed in the tracer fields, even when high-order advection schemes are employed. This behavior is likely associated with the low-order TRiSK discretization used for the fluid depth... A natural extension of this work would be to incorporate the proposed advection fluxes into the momentum equations... Such an extension could lead to a higher-order shallow-water solver and provide greater consistency between tracer advection and the dynamical core.