# Final-project
Property pricing is a convoluted problem influenced by a combination of macro and micro factors. The macro category includes the economic environment, demography, and the general supply and demand in the housing market. The micro factors are the characteristics of the specific properties including a wide range of features such as size, age, number of rooms, availability of garage space, et cetera. 

In our study, we explored first a general model that takes into consideration all the related features we have available. We looked into different model choices, variable selections, and parameter tuning, and reached a lasso model that strikes the optimal balance between precision (variance) and accuracy (bias).

We then extended the exploration further to develop a model that combines both features of specific properties but also a time series analysis which seeks to capture more of the macro influences in the housing market. This model assumes a relatively static relationship between specific features of the houses and the sales prices due to people's general preferences, and forecasts the market averages using an ARIMA model.

The combined model not only incorporates the time series dependence in the underlying data, but also can be practically used for forecasting purposes. To mimic a real life forecasting process, we made every estimate using only historical information. The combined model achieved similar level of accuracy as measure by r-squared as many of the efficacious general models despite the various limitation of the dataset. We think it is a viable solution that has real life application value.

