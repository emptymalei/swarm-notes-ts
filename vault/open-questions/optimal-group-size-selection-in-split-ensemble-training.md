---
created_at: '2026-05-03T05:13:55Z'
source_papers:
- '[[arxiv-260428160-reorganizing-quantum-measurement-records-improves-time-serie]]'
title: Optimal Group Size Selection
---

**Background:** Quantum reservoir computing utilizes repeated circuit executions to generate temporal feature vectors for classical machine learning, with the standard approach averaging all shots at each time step to mitigate noise. Split-ensemble training partitions shot records into multiple groups to provide the readout with several partially denoised feature vectors per time step, though the optimal partitioning strategy remains a challenge.

**Question / Future Work:** The optimal method for selecting the number of groups in split-ensemble training across different hardware constraints and task types is not yet fully determined. Further research is needed to develop a rigorous, non-empirical rule for determining the ideal partition size that maximizes predictive performance while respecting a fixed quantum measurement budget.

**Why It Matters:** Developing a rigorous, analytical rule for optimal shot-record organization would eliminate the need for computationally expensive empirical search, making the method more efficient and scalable for quantum reservoir computing.