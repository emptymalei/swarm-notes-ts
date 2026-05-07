---
created_at: '2026-05-07T05:14:27Z'
source_papers:
- '[[arxiv-260504955-order-based-rehearsal-learning]]'
title: Order vs Graph Sufficiency
---

**Background:** The task of Avoiding Undesired Future (AUF) involves determining optimal interventions to steer system outcomes into a desirable region, typically relying on learned graph structures that are computationally intensive and error-prone.

**Question / Future Work:** There is an open question as to whether the order structure is always sufficient for effective AUF decision-making, or if certain specific system topologies or dependency patterns necessitate the full information provided by an explicit graph structure. Future research is required to characterize the specific system classes or conditions where order-based structures remain insufficient compared to full graph-based approaches.

**Why It Matters:** Establishing the theoretical boundaries of order-based structures is essential for understanding the trade-off between structural simplicity and decision-making performance in complex causal systems.

**Evidence:** An order is less informative than a graph, it can be sufficient to identify the influence of decisions from observational data, suggesting that learning the entire graph is not always necessary.