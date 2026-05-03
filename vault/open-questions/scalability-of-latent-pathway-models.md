---
created_at: '2026-05-03T05:14:20Z'
source_papers:
- '[[arxiv-260427967-differentiable-latent-structure-discovery-for-interpretable]]'
title: Latent Pathway Model Scalability
---

**Background:** Scalability in latent pathway-augmented process convolution models is currently restricted by the joint growth of the feature dimension with the number of basis functions, tasks, and latent pathways.

**Question / Future Work:** Scalability in latent-pathway models needs to be improved, particularly by exploring techniques such as restricting latent components to a subset of nodes or latent unobserved tasks, to allow for larger task sets or more complex pathway structures.

**Why It Matters:** As clinical datasets grow in both the number of patients and the number of physiological variables monitored, the computational bottleneck in latent pathway models limits their applicability to high-dimensional clinical monitoring.

**Evidence:** From a design standpoint, LP-StructGP currently faces scalability limitations. In practice, one must choose either a small number of latent pathways or a small number of tasks... An even more appealing direction would be to restrict latent pathways to latent unobserved tasks.