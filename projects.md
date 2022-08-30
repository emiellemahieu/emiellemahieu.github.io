---
title: Projects
layout: page
---
## Signatures for drawdown paths: A primer



The projects belowt hinge on the concepts of **paths** and **path signatures** as prerequisites. In the words of Terry Lyons[^1]:

> The key idea behind signatures is to stop thinking about a path as a quantity evolving over time, but rather as an object that you can query over intervals. As one queries these intervals, one gets a natural description about what happens with the system at different time scales.

The primer (based on [Chevyrev et al. 2016](https://arxiv.org/abs/1603.03788)) compiles my notes from a literature review on the signature transform, and includes two examples related to portfolio drawdown:

- Classifying high-, medium- and low-drawdown stocks in terms of next period expectation using signature transformed previous period paths as features.
- Distinguishing between high- and low-codrawdown regimes using signature embedded paths.


Download the pdf below:

[Signatures for drawdown paths: A primer](./assets/Signatures_drawdowns_primer.pdf).


----

## Market Generator models: A literature review

**Market generators** are generative machine learning (ML) models with the specificity of modeling financial markets - such as stocks' spot markets, options' vol surfaces and limit order books (market microstructure).

The topic has seen a recent surge in interest, and this literature review provides a (non-exhaustive) list of the most important contributions in the field. Moreover, it discusses the following generative ML architectures in detail:

- Generative Adversarial Networks (GAN)
- Variational Autoencoders (VAE)
- Generative Moment Matching Networks (GMMN)
- Normalizing flow-based autoencoders (NF)

Additionally, the literature review describes how each model can be conditioned on some exogenous state variables X to compose a conditional VAE (CVAE), conditional GAN (CGAN), etc. architecture. A good example would be to condition the simulation on the state-of-the-economy by including leading macro-economic indicators. In a portfolio construction context, the differences in optimal portfolios resulting from the conditional simulation can then be attributed to the conditions and sensitivities analyzed. A very simple example is included in the literature review.

Download the pdf below:

[Market Generator models: A literature review](./assets/Literature_review.pdf).

----


## Portfolio drawdown optimization with generative machine learning 
#### R/Finance conference paper

This short paper was presented at the 2022 R/Finance conference in Chicago, IL. It picks one of the above-mentioned architectures - a CVAE - and introduces a signature-based drawdown reconstruction cost loss term. The result is a host of realistic drawdown scenarios, where the optimal portfolio is defined as the ensemble expectation of min drawdown optimizers.

Download the pdf below:

[Portfolio drawdown optimization with generative machine learning](./assets/Portfolio_drawdown_optimization_with_generative_machine_learning___opportunities_and_pitfalls__RFinance.pdf)



----
## Portfolio drawdown optimization with generative machine learning: A signature approximation approach 
#### Working paper

Work in progress - update and pdf will follow soon.

----

[^1]: Reference to this quote and highly recommended is this introduction to signatures and rough path theory given by Terry Lyons at the Royal Statistical Society in 2022: 


<iframe width="560" height="315" src="https://youtu.be/embed/RnpHG5pRwZ8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>