# Dani Totten's Project Portfolio

# [Project 1: Spatial Statistics - Opioid Deaths in Colorado](https://github.com/dani-totten/spatial_stats)
- Poisson GLM model of expected overdose deaths by county in Colorado, covariates based on CDC research
- Evidence of Spatial Autocorrelation tested with Moran's-I, global statistic that identifies whether or not spatial autocorrelation is present anywhere
- p-values for Moran's-I calculated based on 500 Monte Carlo simulations
- Clusters identified with poisson spatial scan
- South-Central Colorado has a cluster of excess opioid overdose deaths

![](https://github.com/dani-totten/portfolio/raw/main/images/od_death_rate_scaled.png)

# [Project 2: Time Series Analysis - Cocoa Futures Prices](https://github.com/dani-totten/time_series_cocoa)
- Data collected from Yahoo! Finance, Jan 2010-February 2020 with ~250 trading days per year
- Models attempted include ARIMA, dynamic regression, neural net, random walk, time series + ARIMA and random walk
- Identified strong autocorrelation, high volatility and a small but statistically significant effect of El Nino/La Nina on cocoa priced

![](https://github.com/dani-totten/portfolio/raw/main/images/time_series.png)

# [Project 3: Gradient Boosted Regression - King County Housing Prices](https://github.com/dani-totten/gbm)
- Data from Kaggle of 19,933 housing prices in Seattle area
- 3/4 training, 1/4 test split
- Grew 5000 trees based on 14 predictors
- Interaction depth of 1, all trees are stumps and no variable interactions are allowed
- Learning rates of 1, 0.1, 0.01 to look for overfitting
- Best predictions came from lambda = 0.1

![](https://github.com/dani-totten/portfolio/raw/main/images/sample_simple_tree.png)
