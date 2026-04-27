---
created_at: '2026-04-27T05:11:00Z'
source_papers:
- '[[arxiv-260422580-explanation-of-dynamic-physical-field-predictions-using-wass]]'
title: Physically Informed Input Perturbations
---

**Background:** Attribution methods like SmoothGrad rely on point-wise averaging of noisy input gradients, which assumes that noise affects feature importance amplitude symmetrically. However, recent research indicates that input perturbations can cause geometric displacement of attribution maps rather than just amplitude noise.

**Question / Future Work:** There is an unresolved need to develop physically informed input perturbation strategies that move beyond isotropic Gaussian noise. It remains to be explored whether perturbation distributions that respect the governing dynamics of the system being modeled can yield more physically realistic and stable explanations for attribution maps.

**Why It Matters:** Current XAI perturbation methods often ignore the structural properties of physical fields, leading to potentially incoherent explanations that do not align with the underlying dynamics of the modeled domain.

**Evidence:** Standard SmoothGrad and our method both perturb inputs with white Gaussian noise, which is physically uninformed. Replacing isotropic noise with physically informed perturbations could improve the physical realism of the perturbed samples.