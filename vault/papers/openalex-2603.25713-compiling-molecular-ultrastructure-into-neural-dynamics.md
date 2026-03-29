---
# CSL-compatible fields
title: "Compiling molecular ultrastructure into neural dynamics"
author:
  - literal: "Konrad P. Körding"
  - literal: "Anton Arkhipov"
  - literal: "Davy Deng"
  - literal: "Sean Escola"
  - literal: "Seth G. N. Grant"
  - literal: "Gal Haspel"
  - literal: "Michał Januszewski"
  - literal: "Narayanan Kasthuri"
  - literal: "Nina Khera"
  - literal: "Richie E. Kohman"
  - literal: "Grace Lindsay"
  - literal: "Jeantine E. Lunshof"
  - literal: "Adam Marblestone"
  - literal: "David A. Markowitz"
  - literal: "Jordan Matelsky"
  - literal: "Brett D. Mensh"
  - literal: "Patrick Mineault"
  - literal: "Andrew Payne"
  - literal: "Joanne Peng"
  - literal: "Xaq Pitkow"
  - literal: "Philip Shiu"
  - literal: "Gregor F. P. Schuhknecht"
  - literal: "Sven Truckenbrodt"
  - literal: "Joshua T. Vogelstein"
  - literal: "Edward S. Boyden"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25713"

# Custom fields
paper_id: "2603.25713"
paper_source: "openalex"
domain: "neuroscience"
tags:
  - "computational neuroscience"
  - "machine learning for science"
  - "biophysics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ultrastructure-to-dynamics-compiler"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:18:26Z"
created_at: "2026-03-29T20:18:26Z"
---

# Compiling molecular ultrastructure into neural dynamics

**Authors**: Konrad P. Körding, Anton Arkhipov, Davy Deng, Sean Escola, Seth G. N. Grant, Gal Haspel, Michał Januszewski, Narayanan Kasthuri, Nina Khera, Richie E. Kohman, Grace Lindsay, Jeantine E. Lunshof, Adam Marblestone, David A. Markowitz, Jordan Matelsky, Brett D. Mensh, Patrick Mineault, Andrew Payne, Joanne Peng, Xaq Pitkow, Philip Shiu, Gregor F. P. Schuhknecht, Sven Truckenbrodt, Joshua T. Vogelstein, Edward S. Boyden
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25713](https://arxiv.org/abs/2603.25713)

## Summary

This paper proposes a novel framework, the ultrastructure-to-dynamics compiler, to bridge high-resolution, molecularly annotated brain ultrastructure data with local neuronal physiology, such as synaptic efficacies and conductances. The compiler is conceptualized as a learned mapping trained on paired data comprising ultrastructural images and experimental dynamical response measurements. Successfully deploying this compiler would allow anatomical maps to predict circuit dynamics for biophysical simulations, fundamentally changing structure-to-function analysis into a predictive tool. The system is designed to output simulator-ready parameters while explicitly accounting for uncertainty inherent in the translation process.

## Key Contributions

- Introduction of the Ultrastructure-to-Dynamics Compiler, a learned mapping system designed to translate molecularly annotated ultrastructure into physiological parameters.
- The proposed framework shifts structure-to-function analysis from a descriptive approach to a predictive one for biophysical circuit simulations.
- The requirement for paired training data, combining high-resolution imaging (ultrastructure) with dynamical response experiments, is formalized.
- The resulting model would enable forecasting the effects of interventions on neural circuit dynamics directly from anatomical maps.

## Limitations

The primary limitation is the necessity for paired training data, requiring simultaneous acquisition of high-resolution ultrastructure and corresponding dynamical response experiments.

## Key Concepts

- [[ultrastructure-to-dynamics-compiler]]: A learned mapping that translates molecularly annotated ultrastructural data into simulator-ready, uncertainty-aware physiological parameters for neural circuits.

## Archivist Review

One highly central and reusable concept, the Ultrastructure-to-Dynamics Compiler, was approved as it represents a novel learned mapping paradigm bridging structural data to dynamic parameters. No other candidates were strong enough for inclusion, particularly as the paper did not explicitly list any significant open questions. The review focused on approving only the core methodological proposal.

### Approved Concepts
- Ultrastructure-to-Dynamics Compiler: This is the central methodological contribution of the paper, proposing a learned mapping system to bridge structural imaging data to functional simulation parameters.

### Rejected Candidates
- [concept] Predicting Synaptic Efficacy from Structure (`synaptic-efficacy-prediction`) - subcomponent_of_broader_mechanism: Predicting synaptic efficacy is a specific application/output of the main compiler, not the general reusable concept itself.
- [concept] Uncertainty-Aware Physiological Parameters (`uncertainty-aware-parameters`) - subcomponent_of_broader_mechanism: This is a desirable feature/output of the proposed compiler, not a distinct, reusable modeling mechanism itself.

## Links

- [Abstract](https://arxiv.org/abs/2603.25713)
- [PDF](https://arxiv.org/pdf/2603.25713)

