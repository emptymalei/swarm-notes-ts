---
created_at: '2026-04-22T05:05:15Z'
source_papers:
- '[[arxiv-260418727-skillful-global-ocean-emulation-and-the-role-of-correlation]]'
title: Spatially Varying Correlation Loss
---

**Background:** Machine learning models for Earth system emulation often rely on static, globally-averaged covariance structures within loss functions, failing to account for regional or seasonal variations in physical variable dependencies.

**Question / Future Work:** There is a need to develop emulators that utilize spatially and seasonally varying correlation matrices within the loss function to better represent inhomogeneous dynamics. This approach would allow the emulator to resolve region-specific processes, such as boundary current dynamics, which are suppressed by globally averaged covariance structures.

**Why It Matters:** The current use of a globally averaged correlation matrix limits the model's ability to accurately represent regional oceanic phenomena, which is critical for physical realism in data assimilation.

**Evidence:** a future extension will focus on implementing a spatially varying \\mathbf{\\Sigma} (size: lat \\times lon \\times targets \\times targets) to better accommodate the inhomogeneous nature of the global ocean.