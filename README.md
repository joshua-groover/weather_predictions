# weather_predictions for April 15, 2020 (for the 2020 Design, Build, Fly Competition in Witchita, KS)

This repository contains a proof of concept weather pressure Seasonal Autoregressive Integrated Moving Average (SARIMA) model. The purpose of the model is to predict what the air pressure will be for the 2020 Design, Build, Fly Competition. This prediction will be used as an input to the design process.

See the jupyter notebook for a thorough walkthrough of how I built the model and forecasted with it.

**UPDATE** The actual air pressure for April 15, 2020 (scheduled first day of the DBF Competition) in Witchita, KS was 965.12 Millibars. The **model missed the mark by a measley ~.5 millibars**, as it predicted 964.76 millibars with a 95% condifence interval of [961.25, 968.27]. 


Some of the sources/code used:

SARIMA:

https://machinelearningmastery.com/sarima-for-time-series-forecasting-in-python/

https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/

https://www.statsmodels.org/dev/examples/notebooks/generated/statespace_sarimax_stata.html

https://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/

https://towardsdatascience.com/how-to-forecast-sales-with-python-using-sarima-model-ba600992fa7d

AIC:

https://coolstatsblog.com/2013/08/14/using-aic-to-test-arima-models-2/

BIC:

https://pdfs.semanticscholar.org/688f/bcc65c860d4f489ad076ccdc61296a621e52.pdf

Weather Data:

https://www7.ncdc.noaa.gov/CDO/dataproduct
