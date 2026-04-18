---
created_at: '2026-04-18T04:54:39Z'
source_papers:
- '[[arxiv-260413478-deepbullwhip-an-open-source-simulation-and-benchmarking-for]]'
title: Expanding Scope of Bullwhip Simulations
---

**Background:** Real-world supply chains frequently exhibit complex structural characteristics such as multi-product demand with cross-substitution effects, finite capacity, and non-serial (convergent or divergent) topologies. Current bullwhip simulation research remains largely focused on serial chains with unconstrained capacity.

**Question / Future Work:** Future research is required to extend bullwhip simulation frameworks to account for more realistic supply chain network structures, including non-serial topologies, finite upstream capacity constraints (rationing games), and multivariate demand processes where product substitution effects significantly alter inventory dynamics. Integrating these factors into modular simulation engines is necessary to bridge the gap between abstract analytical models and operational reality.

**Why It Matters:** Addressing these limitations is critical for developing digital twins that accurately reflect the constraints and complexities of modern semiconductor and retail supply chains, moving beyond the idealized assumptions that often lead to overly optimistic bullwhip mitigation predictions.

**Evidence:** The current implementation assumes unlimited upstream capacity, precluding study of the rationing game... Demand models in the catalog are univariate; multi-product demand with substitution effects would require extending the demand generator ABC to produce multivariate time series.