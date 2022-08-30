---
title: MSc Theses and Supervision
layout: page
---

## Own MSc Finance theses

##### King's College London: Diversification in an iVaR Framework
<img src="./assets/images/kings.png" alt="drawing" width="70"/>

> **Abstract** This paper addresses some of the oft-quoted shortcomings of standard portfolio construction frameworks. We first argue that because of (1) their risk perception, i.e. the formalization of the risk-reward tradeoff for the ranking of portfolios, and (2) because of their instability, they in practical applications often lack the properties of what we consider a rational portfolio. The proposed algorithms revolve around the construction of diversified portfolios in an iVaR framework. iVaR was introduced by the financial technology firm InvestSuite and embraces the human perception of risk in a portfolio: the frequency of drawdowns, their magnitude, and the time to recover from them. A common challenge in any portfolio construction framework is to make the allocation diversified, i.e. achieving low risk by spreading over many lowly correlated assets rather than over low risk assets in a concentrated way. We delve into the literature to find out what diversification means in the most tractable construction frameworks. We then try to define diversification in an iVaR framework. Next, we compare three distinct viewpoints on how to achieve an optimally diversified iVaR portfolio: maximizing diversification benefits, penalizing excessive concentrations, and recursive optimization on subuniverses or clusters of assets. We backtest these strategies and compare out-of-sample metrics such as risk-adjusted returns and diversification ratios with undiversified iVaR and standard construction frameworks using Hansen’s bootstrapped model confidence set. We finally draw conclusions on which viewpoint proves most valuable for a more rational and robust approach to portfolio construction.

Download the pdf below:

[Diversification in an iVaR Framework](./assets/EMIEL_LEMAHIEU_A09853.pdf)

##### Ghent University: A fractal neural network combination approach to market risk measurement
<img src="./assets/images/ghent.png" alt="drawing" width="70"/>

> **Abstract** This master dissertation revolves around the measurement of market risk. The main methodologies in the field are discussed, focusing on their main limitations. Since these standard models are known to be biased, i.e. under- or overestimating the risk out-of-sample, the thesis proposes a combination approach as to reduce the overall bias. Fractal properties of stock market returns are used to gauge the complexity or roughness of the market. The notion of roughness is intertwined with the assumptions made in standard models through the concept of fractional Brownian motion (fBM). The thesis checks whether measures of roughness contribute to a more effective combination of market risk models. Standard models, together with measures of complexity, are fed into a neural network regression model that is used to recognize and memorize the complex non-linear relationships between the measured complexity, volatility and the eventual risk measure as to minimize the number of unexplained exceedances in loss. The model was trained on Google’s Cloud TPU infrastructure for approximately eight hundred traded assets from eleven countries and ten different industries. The findings imply significant improvements in the combination model when adding roughness as a feature. However, the discussion emphasizes model mindfulness because of the limited convergence of in-sample results due to a set of recurrent data issues. The dissertation expands on the implications for risk managers at financial institutions, as well as for asset managers and traders who use the described methodologies for optimization purposes. The thesis concludes by stressing the crucial point of model mindfulness, since black box risk measurement should always be accompanied by a critical mindset.

Download the pdf below:

[A fractal neural network combination approach to market risk measurement](./assets/RUG01-002784334_2019_0001_AC.pdf)

----

----
## Supervised MSc Theses

##### Simulation of Multivariate Financial Time Series Data for Portfolio Optimization
<img src="./assets/images/rotterdam.png" alt="drawing" width="70"/>

**Laurent Balesse (Erasmus School of Economics, Rotterdam, The Netherlands)**

> **Abstract** This thesis researches different models for the generation of multivariate asset return data including a DCC-GARCH model, a moving block bootstrap model and a Variational Autoencoder (VAE). Their performance is evaluated based on univariate path distribution similarity, univariate stylized facts appearance frequency, and drawdown distribution similarity related to InvestSuite Value at Risk portfolio optimization. The models show significant difference in performance when looking at the test results. Furthermore, the Variational Autoencoder is successfully adapted to improve drawdown distribution similarity between sample and generated data. This result shows the strength and flexibility of the use of artificial networks for financial data generation.


Download the pdf below:

[Simulation of Multivariate Financial Time Series Data for Portfolio Optimization](./assets/Thesis_2021___Financial_time_series_prediction_with_deep_learning-7.pdf)

----

##### Reconciling Risk and Return: an Application combining Momentum and Risk-based Strategies using Machine Learning Techniques
<img src="./assets/images/leuven.png" alt="drawing" width="70"/>

**Pieter Decat & Sebastiaan Jacobs (Katholieke Universiteit Leuven, Leuven Belgium)**

> **Abstract** In bear markets, momentum strategies have traditionally underperformed variance-minimizing strategies displaying larger drawdowns, called momentum crashes. During more benign markets, momentum-based investment strategies have proven to be a persistent way of outperforming market indices across different time horizons and market environments. Simultaneously, research on risk-minimizing strategies has explored new ways of capturing investors’ perceived risk to replace traditional measures like volatility. The iVaR framework minimizes perceived risk, calculated as the average drawdown over the investment horizon. We propose a novel approach that integrates the return-maximizing momentum strategy into the risk-minimizing iVaR framework in order to reconcile both strategies. We do this by using a broad range of machine learning (ML) models to classify assets as winners/losers in a momentum portfolio. This portfolio is then integrated into the iVaR optimization framework, either by requiring a minimum exposure towards momentum winners in the resulting portfolio (constraint-based approach), or by adding a second term to the objective function that minimizes the drawdown relative to the momentum portfolio (objective-based approach). We validate our methodology empirically and find that both the constraint- and objective-based approaches of our mixed strategy portfolios outper- form not only the market, but also single-strategy momentum and iVaR portfolios. This is true across the majority of ML models, with LSTM giving the best results. Our findings indicate that a mixed strategy of momentum and iVaR successfully reconciles both goals of minimizing drawdowns and maximizing returns, and that machine learning improves momentum portfolio performance.

Download the pdf below:

[Reconciling Risk and Return: an Application combining Momentum and Risk-based Strategies using Machine Learning Techniques](./assets/Decat_Jacobs_Momentum.pdf)