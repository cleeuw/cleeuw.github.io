---
title: "The Mean-Field Limit of Hebbian Learning (BSc Thesis)"
excerpt: "Study of mean-field dynamics in deterministic integrate-and-fire biological neural networks. <br/><br/><video autoplay loop muted playsinline style='max-width:600px;height:auto;' src='/images/uspatial;leaky;N=300;I0=0.92;tend=40.0;w0=0.1;u0distr=uniform;r=0.48;w0distr=gaussian;sig1=0.2;sig2=0.5.mp4'></video>"
collection: projects
date: 18-07-2023
author: Cor de Leeuw
---

Supervised by [Oliver Tse](https://otse.win.tue.nl/) and [Jasper Hoeksema](https://research.tue.nl/en/persons/jasper-hoeksema/)

📄 [Report](https://research.tue.nl/en/studentTheses/the-limit-of-learning/)

## Abstract
In this thesis, a model for learning neuronal populations in a spatial setting is constructed, based on a general integrate-and-fire framework.
The focus is on deriving mean-field results that predict neuronal activity and synaptic weight changes in response to each other and external input.
Next to this, synchronization of neuron potentials is also investigated. We find that this tends to occur in excitatory populations.
We present a learning rule based on spike-timing-dependent plasticity (STDP) to model Hebbian learning. In the mean-field limit we show that such a learning rule can coincide with a rate-based learning rule.
The derived mean-field equations predict, under appropriate assumptions, the relation between external (sensory) input, activity, and network structure in the form of a system of partial differential equations.
Numerical simulations using the Julia language are used to illustrate concepts and verify some of the results.
These verifications indicate that the mean-field approximation is valid for at least fully connected homogeneous inhibitory populations.
