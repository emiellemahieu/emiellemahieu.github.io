---
title:  Generating drawdown-realistic markets using path signatures
layout: post
post-image: "../assets/images/image-post-generating.png"
description: Working paper - Generating drawdown-realistic markets with generative AI and path signatures
tags:
- Generative AI
- Market Generators
- Drawdowns
---
----

The simulation of markets with drawdowns that are faithful to empirical market data is a challenging task as drawdown is a path dependent property depending on both the moments of the underlying price process as well as its dynamics such as the occurrence of consecutive losses. In applications, such as pricing drawdown insurance options or developing portfolio drawdown control or optimization strategies, it is paramount that one reproduces this measure correctly in synthetic scenarios. We advocate an essentially non-parametric Monte Carlo approach from machine learning, combining a variational autoencoder generative model with a path signature-based drawdown reconstruction loss function. Machine learning requires a system of differentiable equations that provides numerical simulations by iteration or learning. To overcome issues of numerical complexity and non-differentiability, we approximate drawdown as a linear function of its dynamic or path moments, known in the literature as path signatures. For (fractional) Brownian and empirical data, we obtain excellent approximations using simple linear regression. We then appreciate that drawdown as a linear combination of path moments gives a mathematically non-trivial smoothing (a non-commutative exponential alternative for Taylor series) which gives one leeway to simulate drawdown-realistic markets by including a drawdown evaluation metric in the learning objective. We conclude with a number of numerical experiments on mixed equity, bond, real-estate and commodity portfolios and obtain a host of realistic drawdown scenarios. 

###### Preview 
<iframe src="../assets/Generating_drawdown_realistic_markets_with_path_signatures___PROPOSITIONS (2).pdf#view=FitV" style="width: 70%; height: 50vh"></iframe>

###### Download 
Download the pdf below :

[Generating drawdown-realistic markets using path signatures](../assets/Generating_drawdown_realistic_markets_with_path_signatures___PROPOSITIONS (2).pdf)
