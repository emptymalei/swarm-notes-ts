---
created_at: '2026-04-30T05:14:00Z'
source_papers:
- '[[arxiv-260426422-stlgt-a-scalable-trace-based-linear-graph-transformer-for-ta]]'
title: Adapting to Microservice Topology Drift
---

**Background:** Large-scale microservice systems frequently undergo changes in call paths, service deployments, and routing policies that alter the underlying graph structure. Predictive models for tail latency often assume a fixed dependency structure and struggle to adapt to these non-stationary system topologies.

**Question / Future Work:** Online adaptation to significant topology drift, such as persistent call-path switching or service insertion/removal, remains a limitation for predictors that rely on pre-induced span graphs. Developing methods that can efficiently update or re-learn the dependency representation in response to structural changes without requiring full model retraining is a key challenge for real-world deployment.

**Why It Matters:** Proactive auto-scaling systems require high model reliability; drift in the underlying service topology renders static predictors inaccurate, necessitating automated, efficient adaptation mechanisms to maintain SLO compliance in dynamic environments.