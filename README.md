**Forecasting-Indian-GDP-using-ARIMA**

Gross Domestic Product (GDP) serves as a key performance indicator for an economy, representing the total value of all final goods and services produced within a country in a given year. Widely applied in time series modeling and analysis, GDP data finds extensive use across diverse sectors, including industry, finance, and research institutions.
Accurately predicting GDP is imperative for gaining insights into future economic well-being and formulating effective strategies. These forecasts should provide reliable estimates, guiding the government in developing appropriate economic policies.

The GDP data for the years 1960 to 2022 was collected from the resources provided by the World Bank [3]. The data was processed using Excel tools for the purpose of ARIMA. Python was used for the purpose of modeling, with the ’statsmodels’ library being used. The following process was followed:
• Creating a plot of GDP v/s Time to visualize the GDP
over the years 1960-2022
• Using Augmented Dickey-Fuller test to determine the
order when the series is stationary
• Plotting the ACF and PACF graphs of the stationary
series to determine the presence of Auto-Regression
and Moving Average and find their orders
• Training the ARIMA model on the obtained orders
as ARIMA(p,d,q) on the data from 1960-2017
• Performing diagnostic checks to determine normality
and autocorrelation in the residuals of the ARIMA
model
• Performing prediction for GDP from 2018-2022 and
calculating the RMSE and correlation between the
predictions and the actual values
• Doing a forecast of the GDP values from 2023 up to
2030
