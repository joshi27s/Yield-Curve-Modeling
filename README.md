# Yield-Curve-Modeling


In this research, I have forecasted the yield curve using the dynamic Nelson Siegel model proposed by Dielbold and Li (2006). The files contains MATLAB codes, results and explanations.
This is work in progress.

Synopsis of the Analysis

First, I explored the fequentists' methods of forecasting the yields by decomposing the yields of varying maturities into level, slope, and curvature factors using a simple OLS regression. Then, taking those latent factors, I fitted  reduced form frequentists and Bayesian vector autogregressions (VARs). Among the priors that I  applied are - diffuse, Minnesota, natural conjugate, inverse-Wishart, independent normal and inverse-Wishart, and stochastic search variable selection (SSVS). 
Furthermore, I decomposed the set of yields using principal component analysis, and performed the fitted a frequentist VAR to compare the results. Lastly, I compared the two-step Diebold-Li method with the one-step Kalman filter approach.

To view the latest updates and analysis on the Bayesian and frequentists' methods that I have employed, please check the following google document:
https://docs.google.com/document/d/1h21d4YzXbhRaSbGmOFrSUze3kMl4FU4pbH3COCAuu8I/edit?usp=sharing
