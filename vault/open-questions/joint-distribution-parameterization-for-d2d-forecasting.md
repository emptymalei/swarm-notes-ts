---
created_at: '2026-03-29T20:15:34Z'
source_papers:
- '[[openalex-2603.25370-a-distribution-to-distribution-neural-probabilistic-forecast]]'
title: Scalable joint distribution parameterization
---

**Background:** In distribution-to-distribution neural probabilistic forecasting, the framework is currently implemented at the level of marginal predictive distributions for individual state variables rather than the full joint distribution over the complete state vector.

**Question / Future Work:** Extending the framework to full joint distribution-to-distribution forecasting requires developing scalable parameterisations for high-dimensional dependence structures and covariance representations, which is identified as a substantial challenge not addressed in the current work.

**Why It Matters:** The joint distribution captures essential cross-variable dependencies, and a scalable method for its representation would be crucial for applying the D2D framework to complex, multivariate dynamical systems where correlation structure is important for accurate uncertainty propagation.

**Evidence:** Extending the framework to full joint distribution-to-distribution forecasting would require scalable parameterisations of high-dimensional dependence structures and covariance representations, which remains a substantial challenge and is beyond the scope of the present work.