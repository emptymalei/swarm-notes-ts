---
created_at: '2026-03-29T20:18:23Z'
source_papers:
- '[[openalex-2603.25289-revealing-the-influence-of-participant-failures-on-model-qua]]'
title: Client-side contribution measurement
---

**Background:** In cross-silo Federated Learning (FL), calculating participant contribution metrics like Shapley values (SVs) typically requires access to a centralized server-side dataset.

**Question / Future Work:** Investigate and develop participant contribution measurement methods for cross-silo FL that are accurate yet do not necessitate a server-side dataset, as sharing or using such data is often infeasible in real-world, privacy-sensitive production environments.

**Why It Matters:** The reliance on server-side data for accurate contribution metrics like SVs is a major impediment to deploying FL systems in settings where data sharing is prohibited, making a client-side or shared-data-free alternative essential for wider adoption.

**Evidence:** However, to calculate the SVs, a server-side dataset is required. In many real-world cases, sending a part of the participants data or using a public dataset is not feasible. Here, a suitable measurement is necessary that is precise and does not require server-side data.