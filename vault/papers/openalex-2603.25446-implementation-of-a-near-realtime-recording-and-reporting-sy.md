---
# CSL-compatible fields
title: "Implementation of a Near-Realtime Recording and Reporting System of Solar Radio Bursts"
author:
  - literal: "Peijin Zhang"
  - literal: "Anastasia Kuske"
  - literal: "Bin Chen"
  - literal: "Mengjia Xu"
  - literal: "Gelu M. Nita"
  - literal: "Marin M. Anderson"
  - literal: "Judd D. Bowman"
  - literal: "Ruby Byrne"
  - literal: "Morgan Catha"
  - literal: "Xingyao Chen"
  - literal: "Sherry Chhabra"
  - literal: "Larry D'Addario"
  - literal: "Ivey Davis"
  - literal: "Jayce Dowell"
  - literal: "Katherine Elder"
  - literal: "Dale Gary"
  - literal: "Gregg Hallinan"
  - literal: "Charlie Harnach"
  - literal: "Greg Hellbourg"
  - literal: "Jack Hickish"
  - literal: "Rick Hobbs"
  - literal: "David Hodge"
  - literal: "Mark Hodges"
  - literal: "Yuping Huang"
  - literal: "Andrea Isella"
  - literal: "Daniel C. Jacobs"
  - literal: "Ghislain Kemby"
  - literal: "John T. Klinefelter"
  - literal: "Matthew Kolopanis"
  - literal: "Nikita Kosogorov"
  - literal: "James Lamb"
  - literal: "Casey Law"
  - literal: "Nivedita Mahesh"
  - literal: "Surajit Mondal"
  - literal: "Brian O'Donnell"
  - literal: "Kathryn Plant"
  - literal: "Corey Posner"
  - literal: "Travis Powell"
  - literal: "Vinand Prayag"
  - literal: "Andres Rizo"
  - literal: "Andrew Frederic Romero-Wolf"
  - literal: "Jun Shi"
  - literal: "Greg Taylor"
  - literal: "Jordan Trim"
  - literal: "Mike Virgin"
  - literal: "Akshatha Vydula"
  - literal: "Sandy Weinreb"
  - literal: "Scott White"
  - literal: "D. P. Woody"
  - literal: "Sijie Yu"
  - literal: "Thomas Zentmeyer"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25446"

# Custom fields
paper_id: "2603.25446"
paper_source: "openalex"
domain: "other"
tags:
  - "astrophysics"
  - "real-time systems"
  - "object detection"
  - "data processing"
architectures:
  - "YOLO"
datasets:
  []
concept_slugs:
  - "physics-based-synthetic-burst-generation"
  - "near-realtime-radio-burst-reporting-system"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:18:53Z"
created_at: "2026-03-29T20:18:53Z"
---

# Implementation of a Near-Realtime Recording and Reporting System of Solar Radio Bursts

**Authors**: Peijin Zhang, Anastasia Kuske, Bin Chen, Mengjia Xu, Gelu M. Nita, Marin M. Anderson, Judd D. Bowman, Ruby Byrne, Morgan Catha, Xingyao Chen, Sherry Chhabra, Larry D'Addario, Ivey Davis, Jayce Dowell, Katherine Elder, Dale Gary, Gregg Hallinan, Charlie Harnach, Greg Hellbourg, Jack Hickish, Rick Hobbs, David Hodge, Mark Hodges, Yuping Huang, Andrea Isella, Daniel C. Jacobs, Ghislain Kemby, John T. Klinefelter, Matthew Kolopanis, Nikita Kosogorov, James Lamb, Casey Law, Nivedita Mahesh, Surajit Mondal, Brian O'Donnell, Kathryn Plant, Corey Posner, Travis Powell, Vinand Prayag, Andres Rizo, Andrew Frederic Romero-Wolf, Jun Shi, Greg Taylor, Jordan Trim, Mike Virgin, Akshatha Vydula, Sandy Weinreb, Scott White, D. P. Woody, Sijie Yu, Thomas Zentmeyer
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25446](https://arxiv.org/abs/2603.25446)

## Summary

This paper details the development of a near-realtime system at the Owens Valley Radio Observatory Long Wavelength Array for monitoring solar radio bursts, critical for space weather applications. The system achieves low latency (approx. 10 seconds) by clipping data from a live buffer and generating dynamic spectrograms continuously. These spectrograms are fed into a custom burst identification module based on a YOLO architecture, specifically trained to detect Type III radio bursts. The model's training utilized synthetic Type III bursts generated from a physics-based model, enabling accurate and robust automatic reporting of transient coronal events.

## Key Contributions

- Developed and implemented a near-realtime system at the Owens Valley Radio Observatory Long Wavelength Array for recording and processing solar radio bursts.
- Created a deep-learning-based module, leveraging a YOLO architecture, specifically for the automated identification of Type III solar radio bursts.
- Trained the burst identifier on synthetic Type III radio bursts generated via a physics-based model to ensure high accuracy and robustness.
- Achieved a latency of approximately 10 seconds from radio burst occurrence to automatic reporting via continuous realtime spectrum streaming.

## Limitations

The abstract does not explicitly detail limitations, but the dependence on a physics-based model for synthetic data may introduce systematic biases if the model is incomplete or inaccurate.

## Open Questions & Future Work

- [[multi-type-solar-radio-burst-detection]]

## Key Concepts

- [[physics-based-synthetic-burst-generation]]: A method utilizing physical models of solar coronal processes to synthesize labeled radio dynamic spectrograms for training detection models.
- [[near-realtime-radio-burst-reporting-system]]: An integrated system designed to capture, process, and automatically report solar radio bursts from raw observational data within seconds of occurrence.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Physics-based Synthetic Burst Generation: The use of a physics-based model to generate synthetic training data is a novel approach to overcome the scarcity of real-world, labeled solar radio burst events for deep learning.
- Near-Realtime Radio Burst Reporting System: This is the core application and system developed, integrating data capture, processing, and automated reporting for space weather monitoring with a very low latency goal.

### Approved Open Questions
- Expand burst class training set: Type II bursts are crucial indicators of CME-driven shocks directly relevant to space weather forecasting, making their inclusion a necessary step for a complete operational system.

### Rejected Candidates
- [concept] YOLO (`YOLO`) - not_reusable: The YOLO architecture is a widely known, generic object detection model, not a novel contribution specific to this paper's domain or a reusable methodology itself.

## Links

- [Abstract](https://arxiv.org/abs/2603.25446)
- [PDF](https://arxiv.org/pdf/2603.25446)

