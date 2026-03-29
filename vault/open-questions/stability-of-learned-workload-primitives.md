---
created_at: '2026-03-29T20:16:37Z'
source_papers:
- '[[openalex-2603.25378-prism-dynamic-primitive-based-forecasting-for-large-scale-gp]]'
title: Long-term stability of learned primitives
---

**Background:** Developing compositional forecasting frameworks for complex time series signals like large-scale GPU workloads is an active area of research. These systems attempt to model aggregate behavior by decomposing it into fundamental, interpretable components.

**Question / Future Work:** Investigate the long-term stability and generalizability of the learned primitives ($Q_p$) when applied to future, unseen workload profiles that may exhibit shifts in task types or user base composition beyond the distribution observed during training. This involves determining if the learned primitives remain semantically meaningful and predictive over extended deployment periods without fine-tuning.

**Why It Matters:** The robustness of the learned 'behavioral prototypes' (primitives) is essential for the practical deployment of the model in dynamic, evolving environments like production GPU clusters.

**Evidence:** Crucially, unlike standard latent embeddings, these primitives act as behavioral prototypes, effectively clustering recurrent workload dynamics (e.g., stable periodic cycles vs. transient event bursts) into distinct basis vectors.