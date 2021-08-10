# AFE3-Multivariate-VAR(Vector Auto Regressive)-Modeling
University Trier - Applied Financial Econometrics - Project 3

# Summary for Multivariate VAR Modeling
First we upload the Macro variable dataset and create a monthly inflation rate from the CPI, then declare the three macro variables Federal Fund Rate, Unemployment Rate, and Inflation Rate as a plain time series object and plotit. Afterwards, generate the three VAR models with best fit, then applying the ljung-Box test to check the "No autocorrelation" with chi-sq degrees of freedom 3 and 12. Finally we use the higher plags in VAR and fail to reject the Null Hypothesis "No autocorrelation". Moreover apply the chelosky ordering of macro variables are (Federal Fund Rate, Inflation Rate, unemployment Rate) and plot them. And explain the chelosky decomposition and its interpretation.

# Task done in Multivariate VAR Modeling

1. Load the Macro variable dataset. Calculate yearly inflation rate and remove CPI thereafter.
2. Declare the three macro-variables as plain time series objects. Visualize the resulting data set. What can be inferred in terms of stationarity.
3. Select a three-variable VAR model with the best fit. Estimate it.
4. Is there autocorrelation left. With 12 lags or with 3 lags how is the lag length to be selected for the test.
5. Increase the VAR(p) order and re-estimate the model. Then, repeat the procedure for higher p lags.
6. Pick an ordering and derive the impulse response functions. 
7. Give a short but sufficient interpretation of your results with regard to significance, persistence, and stationarity.

# Summary for Multivariate GARCH Modeling

We use the exchange rate of monthly time series of Euro/USD and British Pound/USD form the Quanld data source. Afterwards, find the best DCC-GRACH model fit for log-return of two time series by using the AIC inforation cirteria. we found the dcca1 (alpha = 0.08) which is not significatly different from 0, that show the correlation bewteen the two time series. And also plot the time- varying correlation.

# Task done in Multivariate GARCH Modeling

1. Find a source for exchange rate data and load monthly series of the Euro/US-Dollar and British Pound/US-Dollar exchange rates into your working environment.
2. Find the DCC-GARCH-model with the best fit for the log-returns of the two exchange rate series.1 Interpret your estimation results.
3. Create a plot of the time-varying correlation implied by DCC-GARCH. Give a detailed interpretation of your result.
