# Time-Series-Forecasting
## Built a model to Forecast monthly sales of Wine for certain Wine Estate for the next 12 month

Analyzed historical monthly sales data of a company. Created multiple forecast models for two different products of a particular Wine Estate and recommended the optimum forecasting model to predict monthly sales for the next 12 months along with appropriate lower and upper confidence limits

# Skills and Tools

    - Exploratory Data Analysis for Time Series Data
    - Exponential Smoothing Models
    - ARIMA/SARIMA Models
    - Moving Average Models

For this particular assignment, the data of different types of wine sales in the 20th century is to be analysed. Both of these data are from the same company but of different wines. As an analyst in the ABC Estate Wines, you are tasked to analyse and forecast Wine Sales in the 20th century.

Data set for the Problem: Sparkling.csv and Rose.csv

Please do perform the following questions on each of these two data sets separately:

  1.Read the data as an appropriate Time Series data and plot the data.
    2.Perform appropriate Exploratory Data Analysis to understand the data and also perform decomposition.
    3.Split the data into training and test. The test data should start in 1991.
    4.Build various exponential smoothing models on the training data and evaluate the model using RMSE on the test data.
      Other models such as regression,naïve forecast models, simple average models etc. should also be built on the training data and check the performance on the test data using       RMSE.
    5.Check for the stationarity of the data on which the model is being built on using appropriate statistical tests and also mention the hypothesis for the statistical test. If       the data is found to be non-stationary, take appropriate steps to make it stationary. Check the new data for stationarity and comment.
      [Note: Stationarity should be checked at alpha = 0.05.]
    6.Build an automated version of the ARIMA/SARIMA model in which the parameters are selected using the lowest Akaike Information Criteria (AIC) on the training data and               evaluate this model on the test data using RMSE.
    7.Build a table with all the models built along with their corresponding parameters and the respective RMSE values on the test data.
    8.Based on the model-building exercise, build the most optimum model(s) on the complete data and predict 12 months into the future with appropriate confidence                        intervals/bands.
    9.Comment on the model thus built and report your findings and suggest the measures that the company should be taking for future sales.
