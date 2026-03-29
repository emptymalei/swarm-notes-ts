---
created_at: '2026-03-29T20:17:52Z'
source_papers:
- '[[openalex-2603.25530-adaptive-subspace-modeling-with-functional-tucker-decomposit]]'
title: Transfer continuity constraint to TT decomposition
---

**Background:** The presented functional Tucker decomposition (FTD) is based on the standard Tucker decomposition structure.

**Question / Future Work:** Transfer the continuity constraint introduced via RKHS modeling from the functional Tucker decomposition (FTD) to alternative tensor decompositions, specifically mentioning the tensor train decomposition.

**Why It Matters:** Applying functional modeling concepts to other popular decompositions like the Tensor Train decomposition could yield powerful new models for structured, continuous data where the low-rank structure of TT might be more appropriate than the full core tensor of TD.

**Evidence:** Further extensions of the present method include adaptations that address missing data or unaligned sampling schemes, in line with [8, 15]. In addition, transferring the continuity constraint to alternative tensor decompositions - such as the tensor train decomposition – presents a promising direction for future work.