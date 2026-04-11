---
created_at: '2026-04-11T04:45:44Z'
source_papers:
- '[[arxiv-260407764-bayesian-tensor-on-tensor-varying-coefficient-model-for-fore]]'
title: Non-linear TOT Modeling Limitations
---

**Background:** Tensor-on-tensor (TOT) models are increasingly used for high-dimensional image-to-image regression, yet most existing formulations rely on rigid linear mappings between input and output tensors. Modeling complex longitudinal neurobiological or physical trajectories often requires capturing inherently non-linear relationships that these standard linear models fail to account for.

**Question / Future Work:** The challenge lies in integrating flexible non-parametric regression—such as Gaussian processes—into high-dimensional tensor-on-tensor frameworks without incurring prohibitive computational costs. Developing scalable Bayesian semi-parametric estimators that maintain spatial structural integrity while capturing non-linear temporal dynamics remains a significant bottleneck.

**Why It Matters:** This is a critical limitation for applying tensor models to real-world, complex longitudinal datasets where physical or biological change is non-linear.

**Evidence:** Most methods assume linear dependencies between the input and output tensors that may not be supported in practical imaging experiments. . . However, the adoption of GPs to tackle non-linearity in TOT regression models is limited, to our knowledge.