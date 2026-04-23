---
created_at: '2026-04-23T05:09:46Z'
source_papers:
- '[[arxiv-260419500-connecting-the-forward-problem-to-the-inverse-problem-in-unc]]'
title: Informative Observation Selection for ESMs
---

**Background:** Earth system model (ESM) parameterizations contain empirical parameters that are often tuned to sparse data, but characterizing physically meaningful parameter uncertainty remains difficult due to the potential for ill-posed inverse problems. The informativeness of observations for parameter calibration is inherently coupled to the multi-scale, spatiotemporal variability of the chaotic dynamical system being modeled.

**Question / Future Work:** The systematic selection of informative observations remains a critical, largely unanswered problem in calibrating Earth system model parameterizations. It is currently unclear how to generalize criteria for choosing optimal observation variables, spatiotemporal averaging lengths, and locations to calibrate chaotic dynamical models without relying on computationally prohibitive, iterative optimal experimental design. Addressing this requires robust methods that can identify parameter identifiability—where the signal from a parameter is distinguishable from observational noise and free from confounding interaction effects—prior to performing the actual Bayesian inference.

**Why It Matters:** This is a fundamental bottleneck in the efficient calibration and uncertainty quantification of Earth system models, replacing expensive iterative trial-and-error observational strategies with a principled, pre-inference framework.

**Evidence:** As a result, the questions of which variables to observe, how they should be averaged, and where and when observations should be collected to calibrate ESM parameterizations remain critical but largely unanswered.