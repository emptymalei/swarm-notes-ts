---
created_at: '2026-03-29T20:17:20Z'
source_papers:
- '[[openalex-2603.25575-topological-optimization-with-birth-and-death-cochains]]'
title: Theoretical stability of cochains
---

**Background:** When using birth and death simplices for topological optimization, their definition can be unstable or ill-defined due to the discrete nature of simplices corresponding to filtration values.

**Question / Future Work:** Explore methods to establish theoretical stability guarantees for $\\epsilon$-birth and $\\epsilon$-death cochains, analogous to the stability of persistence diagrams, especially when the parameter $\\epsilon$ is not infinitesimally small or when the underlying data filtration is highly degenerate.

**Why It Matters:** Establishing theoretical stability for cochains would strengthen their utility as objective functions in optimization by ensuring that the gradient landscape doesn't undergo drastic changes with minor data perturbations.

**Evidence:** While we have good reason not to expect a theoretical guarantee of stability for $\\epsilon\\epsilon$-birth and $\\epsilon\\epsilon$-death cochains, we have a heuristic argument for why they may be more stable than birth and death simplices in practice (see Section 6).