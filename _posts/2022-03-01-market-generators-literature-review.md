---
title:  Market Generator models - A literature review
layout: post
post-image: "../assets/images/image-post-literature-review.png"
description: A literature review of the market generator literature
tags:
- Generative AI
- Market Generators
- Drawdowns
---

**Market generators** are generative machine learning (ML) models with the specificity of modeling financial markets - such as stocks' spot markets, options' vol surfaces and limit order books (market microstructure).

The topic has seen a recent surge in interest, and this literature review provides a (non-exhaustive) list of the most important contributions in the field. Moreover, it discusses the following generative ML architectures in detail:

- Generative Adversarial Networks (GAN)
- Variational Autoencoders (VAE)
- Restricted Boltzmann Machines (RBM)
- Generative Moment Matching Networks (GMMN)
- Normalizing flow-based autoencoders (NF)

Additionally, the literature review describes how each model can be conditioned on some exogenous state variables X to compose a conditional VAE (CVAE), conditional GAN (CGAN), etc. architecture. A good example would be to condition the simulation on the state-of-the-economy by including leading macro-economic indicators. In a portfolio construction context, the differences in optimal portfolios resulting from the conditional simulation can then be attributed to the conditions and sensitivities analyzed. A very simple example is included in the literature review.

###### Preview summary
<iframe src="../assets/Literature_review_slides.pdf#view=FitV" style="width: 70%; height: 50vh"></iframe>

###### Download summary
Download a slide summary below:

[Slide summary - Market Generator models: A literature review](../assets/Literature_review_slides.pdf).

###### Preview main text
<iframe src="../assets/Literature_review.pdf#view=FitV" style="width: 70%; height: 50vh"></iframe>

###### Download main text
Download the full pdf below:

[Market Generator models: A literature review](../assets/Literature_review.pdf).


----