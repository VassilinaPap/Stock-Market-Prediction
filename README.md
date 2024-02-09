# Stock-Market-Return Prediction
### This project aims to have good forecasts of the future price of the S&P500 index so that profitable orders can be placed on time.
In this case study the data was concentrated by trading the S&P 500 market index. The data available for this case study depends on time.

As first step in this case study, we define the prediction tasks. Generally speaking, our goal is to have good forecasts of the future price of the S&P 500 index so that profitable orders can be placed on time. In this study, we calculate an indicator variable (T ) that summarizes the behavior of the price time series in the next k days. The indicators usually try to capture some properties of the prices series, such as if they are varying too much, or following some specific trend, etc.

At the feature selection face, we aim to find thw most adequate subset of available input variables for the modelling task. To select the features to include in our model, we define an initial set of features and then use a technique to estimate the importance of each of these features. Based on these estimates we will select the most relevant features. The first set will be formed by the first 30 years of quotes of S&P 500.

The steps that are followed:
 * use of SQL database to incorporate the data.
 * handle prediction problems with a time ordering among data observations (also known as time series)
 * translating model predictions into decisions and actions in real-world applications.
