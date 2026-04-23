---
created_at: '2026-04-23T05:07:22Z'
source_papers:
- '[[arxiv-260420311-seeing-further-and-wider-joint-spatio-temporal-enlargement-f]]'
title: Scalability of topology-aware memory
---

**Background:** Micro-video popularity prediction often relies on retrieval-augmented frameworks where historical data is stored in memory banks. These banks typically expand linearly with the amount of data, causing challenges in efficiency and scalability as datasets grow.

**Question / Future Work:** The long-term trade-off between memory bank capacity (the number of partitions and clusters) and the ability to capture increasingly nuanced historical popularity patterns as data volumes reach extreme, platform-wide scales remains an open area of investigation. It is not fully resolved how to maintain optimal retrieval performance when the diversity of historical video content exceeds the capacity of a fixed-size topology-aware bank.

**Why It Matters:** This is a fundamental bottleneck for deploying retrieval-augmented popularity prediction systems on large-scale social media platforms, where historical data is massive and non-stationary.

**Evidence:** Instead of directly expanding memory capacity, we update the encoder features of the corresponding clusters when incorporating new videos, enabling unbounded historical association without unbounded storage growth.