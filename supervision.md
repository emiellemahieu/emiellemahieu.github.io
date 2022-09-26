---
title: MSc Theses and Supervision
layout: page
---

## Own MSc Finance theses

##### King's College London: Diversification in an iVaR Framework (2020)
<img src="./assets/images/kings.png" alt="drawing" width="70"/>

> **Abstract** This paper addresses some of the oft-quoted shortcomings of standard portfolio construction frameworks. We first argue that because of (1) their risk perception, i.e. the formalization of the risk-reward tradeoff for the ranking of portfolios, and (2) because of their instability, they in practical applications often lack the properties of what we consider a rational portfolio. The proposed algorithms revolve around the construction of diversified portfolios in an iVaR framework. iVaR was introduced by the financial technology firm InvestSuite and embraces the human perception of risk in a portfolio: the frequency of drawdowns, their magnitude, and the time to recover from them. A common challenge in any portfolio construction framework is to make the allocation diversified, i.e. achieving low risk by spreading over many lowly correlated assets rather than over low risk assets in a concentrated way. We delve into the literature to find out what diversification means in the most tractable construction frameworks. We then try to define diversification in an iVaR framework. Next, we compare three distinct viewpoints on how to achieve an optimally diversified iVaR portfolio: maximizing diversification benefits, penalizing excessive concentrations, and recursive optimization on subuniverses or clusters of assets. We backtest these strategies and compare out-of-sample metrics such as risk-adjusted returns and diversification ratios with undiversified iVaR and standard construction frameworks using Hansen’s bootstrapped model confidence set. We finally draw conclusions on which viewpoint proves most valuable for a more rational and robust approach to portfolio construction.

Download the pdf below:

[Diversification in an iVaR Framework](./assets/EMIEL_LEMAHIEU_A09853.pdf)

----

##### Ghent University: A fractal neural network combination approach to market risk measurement (2019)
<img src="./assets/images/ghent.png" alt="drawing" width="70"/>

> **Abstract** This master dissertation revolves around the measurement of market risk. The main methodologies in the field are discussed, focusing on their main limitations. Since these standard models are known to be biased, i.e. under- or overestimating the risk out-of-sample, the thesis proposes a combination approach as to reduce the overall bias. Fractal properties of stock market returns are used to gauge the complexity or roughness of the market. The notion of roughness is intertwined with the assumptions made in standard models through the concept of fractional Brownian motion (fBM). The thesis checks whether measures of roughness contribute to a more effective combination of market risk models. Standard models, together with measures of complexity, are fed into a neural network regression model that is used to recognize and memorize the complex non-linear relationships between the measured complexity, volatility and the eventual risk measure as to minimize the number of unexplained exceedances in loss. The model was trained on Google’s Cloud TPU infrastructure for approximately eight hundred traded assets from eleven countries and ten different industries. The findings imply significant improvements in the combination model when adding roughness as a feature. However, the discussion emphasizes model mindfulness because of the limited convergence of in-sample results due to a set of recurrent data issues. The dissertation expands on the implications for risk managers at financial institutions, as well as for asset managers and traders who use the described methodologies for optimization purposes. The thesis concludes by stressing the crucial point of model mindfulness, since black box risk measurement should always be accompanied by a critical mindset.

Download the pdf below:

[A fractal neural network combination approach to market risk measurement](./assets/RUG01-002784334_2019_0001_AC.pdf)

----

----
## Supervised MSc Theses

##### Simulation of Multivariate Financial Time Series Data for Portfolio Optimization (2021)
<img src="./assets/images/rotterdam.png" alt="drawing" width="70"/>

**Laurent Balesse (Erasmus School of Economics, Rotterdam, The Netherlands)**

> **Abstract** This thesis researches different models for the generation of multivariate asset return data including a DCC-GARCH model, a moving block bootstrap model and a Variational Autoencoder (VAE). Their performance is evaluated based on univariate path distribution similarity, univariate stylized facts appearance frequency, and drawdown distribution similarity related to InvestSuite Value at Risk portfolio optimization. The models show significant difference in performance when looking at the test results. Furthermore, the Variational Autoencoder is successfully adapted to improve drawdown distribution similarity between sample and generated data. This result shows the strength and flexibility of the use of artificial networks for financial data generation.


Download the pdf below:

[Simulation of Multivariate Financial Time Series Data for Portfolio Optimization](./assets/Thesis_2021___Financial_time_series_prediction_with_deep_learning-7.pdf)

----

##### Reconciling Risk and Return: an Application combining Momentum and Risk-based Strategies using Machine Learning Techniques (2022)
<img src="./assets/images/leuven.png" alt="drawing" width="70"/>

**Pieter Decat & Sebastiaan Jacobs (Katholieke Universiteit Leuven, Leuven, Belgium)**

> **Abstract** In bear markets, momentum strategies have traditionally underperformed variance-minimizing strategies displaying larger drawdowns, called momentum crashes. During more benign markets, momentum-based investment strategies have proven to be a persistent way of outperforming market indices across different time horizons and market environments. Simultaneously, research on risk-minimizing strategies has explored new ways of capturing investors’ perceived risk to replace traditional measures like volatility. The iVaR framework minimizes perceived risk, calculated as the average drawdown over the investment horizon. We propose a novel approach that integrates the return-maximizing momentum strategy into the risk-minimizing iVaR framework in order to reconcile both strategies. We do this by using a broad range of machine learning (ML) models to classify assets as winners/losers in a momentum portfolio. This portfolio is then integrated into the iVaR optimization framework, either by requiring a minimum exposure towards momentum winners in the resulting portfolio (constraint-based approach), or by adding a second term to the objective function that minimizes the drawdown relative to the momentum portfolio (objective-based approach). We validate our methodology empirically and find that both the constraint- and objective-based approaches of our mixed strategy portfolios outper- form not only the market, but also single-strategy momentum and iVaR portfolios. This is true across the majority of ML models, with LSTM giving the best results. Our findings indicate that a mixed strategy of momentum and iVaR successfully reconciles both goals of minimizing drawdowns and maximizing returns, and that machine learning improves momentum portfolio performance.

Download the pdf below:

[Reconciling Risk and Return: an Application combining Momentum and Risk-based Strategies using Machine Learning Techniques](./assets/Decat_Jacobs_Momentum.pdf)

----

##### Currency hedging in an iVaR setting (2022)
<img src="./assets/images/ucl.png" alt="drawing" width="70"/>

**Jannis Fierens (University College London, London, United Kingdom)**

> **Abstract** This paper makes a humble attempt to put currency hedging in a more realistic setting by considering different hedging approaches. Continuously one-to-one hedging is an ex- tremely costly procedure which is why retail investor are advised to construct an optimal basket of currencies for a predetermined period. The literature has recently been focusing on minimising either the minimum or the mean-variance of an international hedged port- folio with a basket of foreign currencies. Other risk measures applied to hedging are Value at Risk and Tail Value at Risk. One could argue that these measures are not capable of entirely capturing what an retail investor perceives as risk. Currency hedging is therefore put in a brand new perspective by considering the state of the art iVaR risk measure. It was introduced by the Belgian financial technology company InvestSuite and embraces the retail perception of risk in a portfolio: the frequency of drawdowns, their magnitude, and the time to recover from them. A rather ambiguous concept in the literature is the definition of hedging applied to the foreign currency market from the perspective of a retail investor. The realistic problem setting inhibits strict bounds for the asset allocation which implies that some methodologies might not be as optimal anymore from a risk per- spective. In particular, the iVaR optimisation problem is compared to a static benchmark and a minimum variance portfolio. This paper does consider different estimates for the covariance matrix. These methods are compared on their out of sample realised volatility, hedging effectiveness, Sharpe ratio, Calmar and pain ratio, cumulative drawdown, aver- age drawdown and average drawdown reduction. Finally, Hansen’s bootstrapped model confidence set is employed to determine if the difference is also statistical significant. This paper finds sufficient evidence that results obtained from constructing a dynamic hedging strategy in a strict setting are not statistically different. These findings should not be attributed to an ill definition or the appropriateness of different methodologies, but rather hinges to the problem setting. For instance, retail investors that seek to mitigate their risk ought not to increase the FX exposure above the level of their initial investment in order to gain diversification benefits. Furthermore, the FX market is characterised by co-movement and clusters of shared risk. Once these strict bounds are relaxed, the methodologies will gain in their effectiveness.

Download the pdf below:

[Currency hedging in an iVaR setting ](./assets/VGXS1.pdf)