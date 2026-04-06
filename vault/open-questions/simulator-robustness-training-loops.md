---
created_at: '2026-04-06T05:02:05Z'
source_papers:
- '[[arxiv-260403087-self-supervised-graph-neural-networks-for-full-scale-tertiar]]'
title: Improving Simulator Robustness
---

**Background:** Tertiary Voltage Control (TVC) in power systems is typically modeled as a Mixed-Integer Non-Linear Program (MINLP), which is computationally expensive for real-time applications. Self-supervised Graph Neural Networks (GNN) offer a promising amortized optimization approach to bypass the high cost of traditional solvers.

**Question / Future Work:** The training loop for GNN-based proxy policies often relies on iterative simulation; however, standard AC power flow simulators frequently fail to converge under the challenging or atypical operating conditions explored during training. Improving the robustness and reliability of these simulators is essential for effective policy learning in physical infrastructure domains.

**Why It Matters:** Simulator convergence is critical for the stability of self-supervised and reinforcement learning frameworks applied to safety-critical physical systems.