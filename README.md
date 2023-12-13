# qq-plot
This Python code defines a function QQ_plots for generating quantile-quantile (QQ) plots to assess the goodness of fit for different probability distribution models (Normal, Exponential, Lognormal, Weibull, Beta, Gamma). The code demonstrates the fitting process for two datasets.

The first dataset, named data, is fitted with both Normal and Exponential distribution models, and their respective AIC (Akaike Information Criterion) values are calculated and printed.

The second dataset, also named data, undergoes the same fitting process for both Normal and Exponential distribution models, with the corresponding AIC values printed.

The code uses the scipy.stats module to fit the specified distribution models, calculate log-likelihood, and compute AIC. Finally, it creates QQ plots for each distribution fit, plotting empirical quantiles against theoretical quantiles, and includes a fitted line.

The output includes AIC values for each distribution fit and the corresponding QQ plots for visual comparison.






