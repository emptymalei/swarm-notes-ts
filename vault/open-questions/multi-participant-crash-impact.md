---
created_at: '2026-03-29T20:18:23Z'
source_papers:
- '[[openalex-2603.25289-revealing-the-influence-of-participant-failures-on-model-qua]]'
title: Impact of concurrent participant failures
---

**Background:** The robustness of model quality to participant failures has primarily been studied with single participant dropouts in current federated learning research.

**Question / Future Work:** Future work should investigate the impact of simultaneous multiple participant crashes within a single FL round, anticipating that the aggregate data loss will likely increase the overall degradation of model quality compared to single-participant failures.

**Why It Matters:** Real-world system failures, particularly network outages, often lead to correlated dropouts across multiple participants, making the simulation of multi-participant failure essential for building resilient FL systems.

**Evidence:** Second, the extended study considered that a single participant crashes during an FL round, which makes analyzing the impact feasible as the change in the data distribution and the impact are easier to trace. Despite that, in a real-world setting, it is possible that multiple participants can crash at the same time due to network failures. We assume that for all dataset types the impact will only increase as more missing participants result in more missing data in the process.