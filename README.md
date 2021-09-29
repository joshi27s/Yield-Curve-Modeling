# Yield-Curve-Modeling


In this research, I have forecasted the yield curve using the dynamic Nelson Siegel model proposed by Dielbold and Li (2006). 

Synopsis of the Analysis

First, I explored the fequentists' methods of forecasting the yields by decomposing the yields of varying maturities into level, slope, and curvature factors using a simple OLS regression. Then, taking those latent factors, I fitted  reduced form frequentists and Bayesian vector autogregressions (VARs). Among the priors that I  applied are - diffuse, Minnesota, natural conjugate, inverse-Wishart, independent normal and inverse-Wishart, and stochastic search variable selection (SSVS). 
Furthermore, I decomposed the set of yields using principal component analysis, and performed the fitted a frequentist VAR to compare the results. Lastly, I compared the two-step Diebold-Li method with the one-step Kalman filter approach.

To view the pre-print on the analysis and the results obtained, please check out the paper given on the link below:
https://arxiv.org/abs/2108.06553
