---
title: "Discretizing Dynamics for Maximum Likelihood Constraint Inference"
date: 2021-09-10
authors: ["Kaylene C. Stocking", "D. Livingston McPherson", "Robert P. Matthew", "Claire J. Tomlin"]
publication_types: ["3"]
abstract: "Maximum likelihood constraint inference is a powerful technique for identifying unmodeled constraints that affect the behavior of a demonstrator acting under a known objective function. However, it was originally formulated only for discrete state-action spaces. Continuous dynamics are more useful for modeling many real-world systems of interest, including the movements of humans and robots. We present a method to generate a tabular state-action space that approximates continuous dynamics and can be used for constraint inference on demonstrations that obey the true system dynamics. We then demonstrate accurate constraint inference on nonlinear pendulum systems with 2- and 4-dimensional state spaces, and show that performance is robust to a range of hyperparameters. The demonstrations are not required to be fully optimal with respect to the objective, and the most likely constraints can be identified even when demonstrations cover only a small portion of the state space. For these reasons, the proposed approach may be especially useful for inferring constraints on human demonstrators, which has important applications in human-robot interaction and biomechanical medicine."
featured: false
publication: "*arXiv: 2109.04874 [cs, eess]*"
url_pdf: "https://arxiv.org/abs/2109.04874"
---
