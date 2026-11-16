---
title: "Global Optimality for Shallow Neural Networks (MSc Thesis)"
excerpt: "Analysis of sufficient conditions for overparameterized two-layer neural networks to converge to a global minimizer of the loss. <br/><br/><video autoplay loop muted playsinline style='max-width:600px;height:auto;' src='/images/geluex;anim;0-1000-150000,T,noth,0,F,T,F,T,F;m=1000;cB=1.0;lam=1e-5;act=gelu;T=F64;MF=T;rep=F;n=30;lrn=10.0;opt=GD.mp4'></video>"
collection: projects
date: 28-10-2025
author: Cor de Leeuw
---

Supervised by [Mark Peletier](https://mpeletie.win.tue.nl/)

📄 [Report](https://research.tue.nl/en/studentTheses/global-optimality-for-shallow-neural-networks/) · 🎞️ [Animations](https://cleeuw.github.io/nn-visualization/)

## Abstract
We formulate the training process of a shallow neural network with a possibly nonsmooth activation function as a gradient flow, and establish definability as a sufficient condition for the existence of a (non-unique) global solution.
Interpreting the flow as a Wasserstein gradient flow as in [Chizat & Bach (2018)](#CB18) and [Wojtowytsch (2020)](#Woj20) leads us to an optimality criterion in terms of an auxiliary function \\( G \\), and a guarantee of escape from nonoptimal network states if the weights are sufficiently omnidirectional.
We extend the latter to finite-width networks with nonsmooth activation functions.
The optimality that one would expect based on these results is contrasted to early-alignment-induced convergence of a ReLU-network to a nonoptimal function from [Boursier & Flammarion (2025)](#BF25), which illustrates how omnidirectionality can be lost if the activation function is not differentiable and the initialization is small.
We illustrate the results numerically.

## References

- <a id="CB18"></a> Chizat, Lénaïc, and Francis Bach. ‘On the Global Convergence of Gradient Descent for Over-Parameterized Models Using Optimal Transport’. Advances in Neural Information Processing Systems 31 (2018). <https://proceedings.neurips.cc/paper_files/paper/2018/hash/a1afc58c6ca9540d057299ec3016d726-Abstract.html>.
- <a id="Woj20"></a> Wojtowytsch, Stephan. ‘On the Convergence of Gradient Descent Training for Two-Layer ReLU-Networks in the Mean Field Regime’. arXiv:2005.13530. Preprint, arXiv, 27 May 2020. <https://doi.org/10.48550/arXiv.2005.13530>.
- <a id="BF25"></a> Boursier, Etienne, and Nicolas Flammarion. ‘Early Alignment in Two-Layer Networks Training Is a Two-Edged Sword’. Journal of Machine Learning Research 26, no. 183 (2025): 1–75. <http://jmlr.org/papers/v26/24-1523.html>.
