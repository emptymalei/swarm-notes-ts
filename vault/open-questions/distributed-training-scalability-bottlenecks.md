---
created_at: '2026-05-03T05:15:27Z'
source_papers:
- '[[arxiv-260427431-a-study-on-the-performance-of-distributed-training-of-data-d]]'
title: Distributed training scalability bottlenecks
---

**Background:** Deep learning models often encounter challenges in scaling distributed training across multiple GPU accelerators, particularly when the neural network architecture is relatively small compared to the large volume of training data.

**Question / Future Work:** Research is required to analyze the communication overhead and synchronization bottlenecks in multi-GPU distributed deep learning frameworks when applied to scientific simulations with high-throughput training data requirements.

**Why It Matters:** Communication overhead relative to compute intensity remains a fundamental scaling limitation for scientific machine learning surrogate modeling.