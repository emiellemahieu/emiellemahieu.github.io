---
title: Research Projects
layout: page
---
## Signatures for drawdown paths: A primer



The projects below hinge on the concepts of **paths** and **path signatures** as prerequisites. In the words of Terry Lyons[^1]:

> The key idea behind signatures is to stop thinking about a path as a quantity evolving over time, but rather as an object that you can query over intervals. As one queries these intervals, one gets a natural description about what happens with the system at different time scales.

The primer (based on [Chevyrev et al. 2016](https://arxiv.org/abs/1603.03788)) compiles my notes from a literature review on the signature transform, and includes two examples related to portfolio drawdown:

- Classifying high- and low-drawdown stocks in terms of next period expectation using signature transformed previous period paths as features.
- Distinguishing between high- and low-codrawdown regimes using signature embedded paths.


Download the pdf below:

[Signatures for drawdown paths: A primer](./assets/Signatures_drawdowns_primer.pdf).


----

## Market Generator models: A literature review

**Market generators** are generative machine learning (ML) models with the specificity of modeling financial markets - such as stocks' spot markets, options' vol surfaces and limit order books (market microstructure).

The topic has seen a recent surge in interest, and this literature review provides a (non-exhaustive) list of the most important contributions in the field. Moreover, it discusses the following generative ML architectures in detail:

- Generative Adversarial Networks (GAN)
- Variational Autoencoders (VAE)
- Restricted Boltzmann Machines (RBM)
- Generative Moment Matching Networks (GMMN)
- Normalizing flow-based autoencoders (NF)

Additionally, the literature review describes how each model can be conditioned on some exogenous state variables X to compose a conditional VAE (CVAE), conditional GAN (CGAN), etc. architecture. A good example would be to condition the simulation on the state-of-the-economy by including leading macro-economic indicators. In a portfolio construction context, the differences in optimal portfolios resulting from the conditional simulation can then be attributed to the conditions and sensitivities analyzed. A very simple example is included in the literature review.

Download a slide summary below:

[Slide summary - Market Generator models: A literature review](./assets/Literature_review_slides.pdf).

Download the full pdf below:

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

----
## Drawdown as a non-linear dynamic system 
#### Support document

One way to appreciate the universal non-linearity of the signature - which we referred to in the generative ML paper as the signature universal approximation theorem - is to stop thinking about our drawdown functional as a closed-form formula, but rather as a dynamic (differential) system, and to see the signature as part of the solution of a controlled differential equation, i.e. the change in drawdown of a portfolio as 'controlled' by the changes in the underlying portfolio value path. This non-linear (but sufficiently smooth) system can be approximated in a Taylor series-like fashion using linear coefficients on the signature. Taylor approximation of a polynomial f of order k tells us exactly that differentiating f k times will yield constants. Taylor's theorem tells us that for a feature X the linear algebra on the power series x^k, k in [0, 1, ...[ is then dense in the polynomial space of X. Hence, by generating these features and applying linear regression we can get arbitrary close approximation of f, since the power series provide 'natural basic functions'. 


When X is not a scalar but a path, the signature terms play the role of the natural basic functions, i.e. the monoids in the path space. This follows naturally when thinking of f as the solution of a differential equation driven by the path X. For linear paths (e.g. time) and linear interactions between f and X, one gets exactly Taylor approximation. The role of the signature is to generalize X to paths, and to generalize f to smooth functions in the Lipschitz (bounded differentials) sense.


In this support document to the generative ML paper above, we discuss that, for paths of bounded variation, the drawdown of a path is bounded by the variation of the path, such that this approximation makes sense. We reiterate the main messages from rough path theory, propose drawdown as a non-linear dynamic system and discuss the adequacy of these regressions on real  world data.

Download the pdf below:

[Portfolio drawdown optimization with generative machine learning](./assets/Drawdown_as_a_non_linear_dynamic_system%20(10).pdf)

----

----
## Identifying common sources of drawdown risk: dimension reduction and portfolio selection 
#### Working paper

Work in progress

----

----

[^1]: Reference to this quote and highly recommended is this introduction to signatures and rough path theory given by Terry Lyons at the Royal Statistical Society in 2022 included above. 

### References
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/RnpHG5pRwZ8?start=117" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>