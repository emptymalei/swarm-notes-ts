---
created_at: '2026-05-16T05:11:45Z'
source_papers:
- '[[arxiv-260514840-in-context-learning-for-data-driven-censored-inventory-contr]]'
title: Identifiability in Censored Demand
---

**Background:** In censored inventory control, demand is partially observed depending on the chosen action, creating a trade-off between minimizing immediate costs and gathering information to reduce future uncertainty. Under severe censoring, standard data-driven methods often face identifiability challenges where the learner cannot distinguish between different demand distributions in the tail regions.

**Question / Future Work:** Future work is needed to determine the exact conditions and limits of identifiability for latent demand distributions in the presence of decision-dependent right-censoring, particularly to establish whether specific exploration strategies can enable consistent estimation of the demand tail. This is critical for quantifying fundamental information loss and for designing policies that achieve optimal regret under extreme censoring regimes.

**Why It Matters:** Understanding these identifiability barriers is essential for developing theoretically sound algorithms that can handle real-world inventory settings with extreme stockout rates where traditional estimation techniques fail.