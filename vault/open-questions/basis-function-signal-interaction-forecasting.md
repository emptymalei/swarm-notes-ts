---
created_at: '2026-04-28T05:15:53Z'
source_papers:
- '[[arxiv-260423968-decompkan-decomposed-patch-kan-for-long-term-time-series-for]]'
title: Basis Function Signal Interaction
---

**Background:** The selection of basis functions (e.g., B-splines, Fourier, RBF) within neural network architectures fundamentally constraints the functional space available for learning time-series dynamics.

**Question / Future Work:** There is an unresolved need to systematically investigate how different basis functions interact with signal structures in time-series forecasting, particularly determining which signal characteristics make specific bases (e.g., Fourier vs. Spline) superior for generalizable performance.

**Why It Matters:** Defining the relationship between basis functions and signal dynamics is crucial for advancing the design of functional, interpretable neural architectures for time series.

**Evidence:** A rigorous study of alternative basis functions (Fourier, Chebyshev, RBF, Gabor) within the decomposed Patch-KAN framework... as preliminary synthetic experiments (Appendix D) suggest that basis choice interacts with signal structure in ways that merit deeper investigation.