---
title: "The Effect of Initialization in CNNs for Sign Language Digit Recognition (Course Project)"
excerpt: "Investigation of different weight initialization strategies for a convolutional neural network tasked to classify sign language digits." # <br/><br/><img style='max-width:600px;height:auto;' src='/images/7_sign_language.jpg' alt='7 in sign language'/>"
collection: projects
date: 09-01-2025
authors:
  - Jeroen van Heijst
  - Cor de Leeuw
---

📄 [Report & Code](https://github.com/cleeuw/mathnn)

## Abstract
We investigate weight initialization strategies for a convolutional neural network trained to classify American Sign Language digits (0–9). Using the architecture of [Mavi (2020)](#Mavi) as a baseline, we show that correcting a subtle misconfiguration in PyTorch's default Kaiming initialization substantially accelerates convergence. We further find that initializing the first convolutional layer with classical edge-detection kernels yields no statistically significant improvement over proper Kaiming initialization, suggesting that generic edge detectors are not especially useful for this specific image classification task.

## Reference
<a id="Mavi"></a> Mavi, Arda. ‘A New Dataset and Proposed Convolutional Neural Network Architecture for Classification of American Sign Language Digits.’ arXiv:2011.08927. Preprint, arXiv, 16 November 2020. <https://doi.org/10.48550/arXiv.2011.08927>.
