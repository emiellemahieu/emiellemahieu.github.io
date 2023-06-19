---
title:  Explainable data-driven portfolio construction with conditional bootstrapped Shapley values
layout: post
post-image: "../assets/images/image-post-explainability.png"
description: Working paper - Explaining DGP-free portfolio construction with SHAP values
tags:
- Generative AI
- Market Generators
- Drawdowns
---
----

Data-driven portfolio construction is non-parametric in the sense that it does not impose its objective on a parametric representation of input paths, such as a variance-covariance matrix, but rather imposes its objective directly on these paths without having to make assumptions on their underlying data generating process (DGP). The advantage is thus that one can optimize on much richer dynamics than typical DGP assumptions, e.g. Gaussian assumptions behind mean-variance optimization. The main disadvantage is that one can seemingly interpret the parameters that gave rise to the optimal portfolios not that easily anymore, and for instance do sensitivity analysis, i.e. how will the portfolio change when parameter x or y in- or decreases? This is conducive to the black box perception of increasingly more data-driven portfolio construction tools. However, tools from explainable AI such as Shapley values, which are mathematically principled contribution estimators of features to their output, can be used to overcome this issue. We advocate a novel approach that combines the powerful statistical approach of conditional bootstrapping with Shapley values that attribute changing optimal portfolio weights to changing market conditions. The empirical usefulness is shown on a US equity portfolio backtest, where the portfolio manager gets a better insight in his or her portfolio composition and its sensitivity to changing market conditions.

###### Preview 
<iframe src="../assets/Explainable_non_parametric_portfolio_construction_with_conditional_bootstrapped_Shapley_values (9).pdf#view=FitV" style="width: 70%; height: 50vh"></iframe>

###### Download 
Download the pdf below:

[Explainable data-driven portfolio construction with conditional bootstrapped Shapley values](../assets/Explainable_non_parametric_portfolio_construction_with_conditional_bootstrapped_Shapley_values (9).pdf)

----
