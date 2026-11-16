---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on the qualitative behaviour of coupled nonlinear
dynamical systems. I combine numerical simulation, machine-learning
classification and mathematical analysis to investigate how system
behaviour changes with parameters and interactions.

I am a volunteer research assistant at Kyiv National University, supervised
by **Prof. Ihor Samoilenko** and **Assoc. Prof. Roman Yakymiv**. This work is
also integrated with my final-year BSc Computer Science project at the
University of London.

[View research notebooks on GitHub](https://github.com/timgrego/RA-Work){: .btn .btn--primary}

## Qualitative dynamics in coupled nonlinear systems

**Ongoing research · October 2025–present**

### Research problem

Coupled nonlinear systems can exhibit substantially different behaviours
depending on their parameters and the interactions between their components.
Identifying these behaviours through simulation becomes difficult when
the parameter space is large and many configurations produce invalid
or divergent dynamics.

My work investigates how to explore this parameter space efficiently,
distinguish dynamical regimes and understand transitions between them.

### Model

The initial model describes two interacting locations, each with local
Lotka–Volterra dynamics. These local dynamics are combined with
normalisation and a conflict mechanism to construct a nonlinear
discrete-time system.

The central question is how the local parameters and coupling between
locations determine the qualitative behaviour of the full system.

### My contributions

- **Numerical simulation:** implemented the model and reproduced results
  from earlier work by my supervisors.
- **Parameter-space exploration:** developed sampling and visualisation
  methods to investigate the distribution of dynamical regimes.
- **Machine-learning classification:** investigated an initial
  Gaussian-process approach and developed separate classifiers for
  validity and stable versus oscillatory behaviour.
- **Mathematical analysis:** developed a numerical criterion for detecting
  regime transitions and investigated the assumptions needed to justify
  its interpretation through stability and bifurcation theory.

### Methodological development

A central challenge has been the presence of substantial regions of
invalid dynamics. This motivated separating two questions: whether a
parameter configuration produces admissible dynamics, and which regime
occurs within the valid region.

My theoretical work investigates the conditions under which changes detected by the numerical criterion imply a bifurcation in the underlying dynamical system.

## Current extension: information diffusion and control

**Final-year project · Ongoing**

My University of London final-year project,
*Predictive Modelling of Social Media Trend Emergence*, extends this
research towards information diffusion on social-media platforms.

The current direction replaces the Lotka–Volterra component with a
discretised information-warfare model while retaining the coupled-system
framework.

The planned investigation comprises:

1. **System identification:** estimate model parameters using public
   Telegram data.
2. **Predictive validation:** assess how well the fitted model reproduces
   and predicts observed dynamics.
3. **Regime analysis:** investigate the qualitative behaviour of the
   fitted system.
4. **Control:** explore model predictive control for specified objectives
   under constraints.

These components are ongoing or planned work, rather than completed results.

## Broader research interests

My experience has motivated an interest in the relationship between a
system’s qualitative dynamics and the behaviours it can realise.

I am particularly interested in:

- Nonlinear dynamical systems, stability and bifurcations.
- Control, robustness and behavioural realisability.
- The mathematical foundations of autonomous and adaptive systems.

In the longer term, I hope to investigate how adaptive and goal-directed
behaviour can arise through interactions within dynamical systems.

## Research materials

The repository contains notebooks documenting the development of the
research, including exploratory experiments and earlier approaches.

[Browse the research repository](https://github.com/timgrego/Qualitative-Dynamics-in-Coupled-Nonlinear-Systems)

<!-- Add links to the proof and presentation once public versions are available.
Use their actual paths, and label working notes with their review status.
-->