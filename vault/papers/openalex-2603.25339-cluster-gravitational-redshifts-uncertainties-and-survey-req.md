---
# CSL-compatible fields
title: "Cluster gravitational redshifts: uncertainties and survey requirements"
author:
  - literal: "Eleni Tsaprazi"
  - literal: "Giorgio F. Lesci"
  - literal: "Federico Marulli"
  - literal: "Alan F. Heavens"
  - literal: "Enrico Maraboli"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25339"

# Custom fields
paper_id: "2603.25339"
paper_source: "openalex"
domain: "cosmology"
tags:
  - "cosmology"
  - "gravitational lensing"
  - "modified gravity"
  - "galaxy clusters"
  - "forecasting"
architectures:
  []
datasets:
  - "Spectroscopic Stage-5 Experiment"
  - "Widefield Spectroscopic Telescope"
concept_slugs:
  - "cluster-gravitational-redshifts-modified-gravity-probe"
  - "linear-rescaling-gravitational-potential-alpha-mg"
dataset_slugs:
  - "spectroscopic-stage-5-experiment"
  - "widefield-spectroscopic-telescope"
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:19:10Z"
created_at: "2026-03-29T20:19:10Z"
---

# Cluster gravitational redshifts: uncertainties and survey requirements

**Authors**: Eleni Tsaprazi, Giorgio F. Lesci, Federico Marulli, Alan F. Heavens, Enrico Maraboli
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25339](https://arxiv.org/abs/2603.25339)

## Summary

This paper investigates the precision achievable for constraining modified gravity using cluster gravitational redshifts ($z_g$) by employing an end-to-end forecasting pipeline that incorporates various observational and theoretical uncertainties. The authors simulate cluster catalogs using a generative model with a five-parameter Halo Occupation Distribution (HOD) to parameterize deviations from General Relativity via the parameter $\alpha_{\mathrm{MG}}$. Key findings indicate that the intracluster velocity dispersion sets a fundamental limit on redshift precision improvements, and that accurate determination of cluster centers is crucial as mis-centring can mimic new physics signals in high Signal-to-Noise surveys. Consequently, the study suggests that shallow, narrower spectroscopic surveys are superior to deep, wide photometric surveys for constraining modified gravity models using this probe.

## Key Contributions

- Developed an end-to-end forecasting pipeline to model observational and theoretical uncertainties affecting cluster gravitational redshifts as a probe of modified gravity.
- Determined that intracluster velocity dispersion imposes an effective floor, showing that redshift precision better than $\sigma_z\sim 10^{-4}(1+z)$ yields no further improvement in the precision of the modified gravity parameter $\alpha_{\mathrm{MG}}$.
- Found that shallow, narrower spectroscopic surveys are favored over deep, wide photometric surveys for achieving precise modified gravity constraints.
- Showed that mis-centring of cluster centers can mimic significant departures from General Relativity, making accurate center determination essential for upcoming high-S/N surveys.

## Limitations

The analysis relies on specific modeling assumptions for the halo occupation distribution (HOD) and density profiles (e.g., NFW profile for baryonic deviations).

## Open Questions & Future Work

- [[modified-gravity-models-after-gw170817]]
- [[accurate-cluster-center-proxies]]

## Key Concepts

- [[cluster-gravitational-redshifts-modified-gravity-probe]]: Utilizing the gravitational redshift effect observed in galaxy clusters to parameterize deviations from General Relativity via the parameter $\\alpha_{\\mathrm{MG}}$.
- [[linear-rescaling-gravitational-potential-alpha-mg]]: A single parameter used to linearly rescale the gravitational potential, quantifying the magnitude of modifications to General Relativity in cluster observations.

## Archivist Review

Two key concepts were approved: the primary application of cluster gravitational redshifts to constrain modified gravity, and the specific parameter ($\\alpha_{\\mathrm{MG}}$) used for quantification. Two future survey experiments were approved as they represent critical, named resources for future constraint validation. Two explicit open questions were retained: one addressing the required theoretical scope (post-GW170817 models) and another addressing the most critical systematic uncertainty identified (cluster center determination). The remaining candidates were rejected as they were either standard modeling components, paper-local findings, or less impactful suggestions for future work, adhering to the scarcity constraint.

### Approved Concepts
- Cluster Gravitational Redshifts as a Modified Gravity Probe: This work specifically frames the measurement of cluster gravitational redshifts ($z_{g}$) as a primary tool for constraining modified gravity (MG) models, going beyond standard cosmological probes.
- Linear Rescaling of Gravitational Potential ($\\alpha_{\\mathrm{MG}}$): $\\alpha_{\\mathrm{MG}}$ is the specific, central parameter used by the authors to quantify any deviation from General Relativity, making it the key observable derived from the analysis.

### Approved Open Questions
- Investigate post-GW170817 gravity models: This is crucial for connecting observational constraints from gravitational redshifts to the next generation of viable modified gravity theories beyond General Relativity.
- Efforts on accurate cluster center proxies: Cluster center mis-specification is identified as the only systematic effect capable of mimicking significant departures from General Relativity, making its accurate determination paramount for Stage-IV and Stage-V precision cosmology.

### Rejected Candidates
- [concept] Halo Occupation Distribution (HOD) (`halo-occupation-distribution-hod`) - subcomponent_of_broader_mechanism: The HOD is a standard modeling component in galaxy-halo connection studies and not a novel, central methodological contribution specific to this paper's core novelty regarding uncertainty propagation for gravitational redshifts.
- [concept] End-to-End Forecasting Pipeline (`end-to-end-forecasting-pipeline`) - generic: This is a general approach to uncertainty analysis common in experimental physics/cosmology forecasting rather than a specific reusable algorithmic concept.
- [concept] Preference for Shallow, Narrow Spectroscopic Surveys (`shallow-narrow-spectroscopic-surveys-preference`) - paper_local: This is a direct conclusion about survey design based on the analysis, not a reusable, self-contained methodological concept.
- [concept] Mis-Centring Mimicking New Physics (`mis-centring-mimicking-new-physics`) - paper_local: This is a specific finding about a systematic effect, not a reusable general ML/forecasting mechanism.
- [open_question] Develop high-resolution simulations of structure formation in modified gravity models (`high-resolution-mg-simulations-self-consistent-halos`) - low_impact: This is explicitly framed as future work building upon a limitation of the current study's modeling choices.
- [open_question] Explore alternative gravity parameterizations (`explore-alternative-mg-parameterizations`) - other: This is a clear, general future direction for model exploration, making it a worthy open question. However, given the scarcity constraint and the presence of a question about post-GW170817 models, this is slightly less focused on a direct methodological bottleneck. (Keeping the other, more specific ones). Rejected due to scarcity limit and overlap with parameter space exploration implied elsewhere.
- [open_question] Adopt full 3D velocity modeling (`full-3d-jeans-equation-velocity-modeling`) - other: This is a specific future improvement to the dynamical modeling component rather than a fundamental unresolved bottleneck for the entire field. Rejected due to scarcity limit.

## Datasets

- [[spectroscopic-stage-5-experiment]]
- [[widefield-spectroscopic-telescope]]

## Links

- [Abstract](https://arxiv.org/abs/2603.25339)
- [PDF](https://arxiv.org/pdf/2603.25339)

