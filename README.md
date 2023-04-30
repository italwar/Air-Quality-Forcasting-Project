## Air-Quality-Forcasting-Project

Air Quality Forcasting Project(CO2 Emission)

Business Objective :  TO Forecast CO2 level for an organization can follow governement norms with respect to CO2 emission levels.

This project forecast the carbon Dioxide (CO2) emission levels, so that organization have to follow agovernment norms with respect to co2 emission and they have to pay charges accordingly. In this project the main component is data.

using transformation (like = Scalling , min-max scalling, quantile transformations) to make time series stationary we have to remove trend and seasonality rom it, before that we use dickey fuller test to make sure our time series is non-stationary)

And Smooting techniques also used to observe trend in time series as well as to predict the future values. But performance of the other models was good compared to smoothing techniques.

Build the Model on (stationary data and non-stationary data) like Autoregressor, ARIMA( Auto Regressive Integrated Moving Avarage, Auto ARIMA Holt's smoothing techniques.

Performed of different models measured by RMSE - 1.0268( root means absolute error) and MAE - 0.0542(Mean absolute error) as we are predicting future co2 emission.

We have deployd ARIMA model on streamlit.
