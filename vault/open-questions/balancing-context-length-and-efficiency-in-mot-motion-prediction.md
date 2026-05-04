---
created_at: '2026-05-04T05:16:10Z'
source_papers:
- '[[arxiv-260500362-time-series-meets-complex-motion-modeling-robust-and-computa]]'
title: Context Length vs Efficiency in MOT
---

**Background:** Multi-object tracking (MOT) relies on motion predictors to forecast future object positions, a task that remains challenging when objects exhibit complex, non-linear trajectories. While generative and autoregressive models have been employed, they often introduce significant computational overhead and susceptibility to cumulative prediction errors.

**Question / Future Work:** Research is needed to investigate the optimal balance between model depth, receptive field size, and computational efficiency for motion prediction in MOT. Specifically, there is an open question regarding how to develop adaptive context-length mechanisms or hierarchical temporal models that improve performance on long-range or highly volatile non-linear trajectories without compromising real-time constraints.

**Why It Matters:** Managing long-range temporal dependencies without prohibitive computational costs is a fundamental bottleneck for real-time motion prediction in complex environments.