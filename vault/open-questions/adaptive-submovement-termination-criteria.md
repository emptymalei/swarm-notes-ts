---
created_at: '2026-04-23T05:06:03Z'
source_papers:
- '[[arxiv-260420673-short-time-wavelet-inspired-mouse-submovement-detection]]'
title: Adaptive submovement termination criteria
---

**Background:** Submovement decomposition algorithms often rely on termination criteria to determine when no further meaningful components exist in the residual signal. Selecting appropriate thresholds for stopping this iterative process is essential to avoid over-fitting noise or failing to capture true submovements.

**Question / Future Work:** There is a need for robust, task-dependent, or adaptive termination criteria that can distinguish between meaningful submovements and residual noise. Current heuristics remain sensitive to model misfits and varying signal-to-noise ratios, calling for a more formal or probabilistic approach to determining when to halt decomposition.

**Why It Matters:** Automated and reliable termination of submovement extraction is a primary bottleneck in applying these methods to real-world datasets where ground truth labels are absent and motion profiles vary significantly across populations or tasks.

**Evidence:** Additional decomposition loop termination criteria can, and should, be investigated depending on the use of the decomposition strategy.