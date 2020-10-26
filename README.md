# Dani Totten's Project Portfolio


# [Project 1: Spatial Statistics - Opioid Deaths in Colorado](https://github.com/dani-totten/spatial_stats)
# Opioid deaths in Colorado
- Poisson GLM model of expected overdose deaths by county in Colorado, covariates based on CDC research
- Evidence of Spatial Autocorrelation tested with Moran's-I, global statistic that identifies whether or not spatial autocorrelation is present anywhere
- p-values for Moran's-I calculated based on 500 Monte Carlo simulations
- Clusters identified with poisson spatial scan
- South-Central Colorado has a cluster of excess opioid overdose deaths
![](https://github.com/dani-totten/portfolio/blob/main/images/od_deathrate_map.png)
# [Project 2: Time Series Analysis - Cocoa Futures Prices](https://github.com/dani-totten/time_series_cocoa)
- Data collected from Yahoo! Finance, Jan 2010-February 2020 with ~250 trading days per year
- Models attempted include ARIMA, dynamic regression, neural net, random walk, time series + ARIMA and random walk
- identified strong autocorrelation, high volatility and a small but statistically significant effect of El Nino/La Nina on cocoa priced

# [Project 3: Gradient Boosted Regression - King County Housing Prices](https://github.com/dani-totten/gbm)
- Data from Kaggle of 19,933 housing prices in Seattle area
- 3/4 training, 1/4 test
- Grew 5000 trees based on 14 predictors
- learning rates of 1, 0.1, 0.01. Best predictions came from lambda = 0.1

# [Project 4: Extreme Value Theory - GEV distribution goodness-of-fit to order statistic](https://github.com/dani-totten/masters_project)
- Master's project in statistics, Fall 2020
- Generalized extreme value (GEV) distribution for modeling behavior in model tails
- Extremal types theorem is like the central limit theory, but for maxima in a given period
- block sizes impact GEV distribution
- simulated a known distribution to model maximum based on distribution of order statistics to compare GEVs from different block sizes to the the true maxima using goodness of fit tests
