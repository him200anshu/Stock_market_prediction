# Stock Market Prediction

The Stock Market Prediction Project seeks to utilize machine learning and data analysis to forecast stock price movements. In today's financial landscape, accurate predictions are essential for informed decision-making and optimizing investment strategies.

With advanced computational techniques and extensive historical market data, machine learning algorithms offer a promising approach to predicting stock prices with greater accuracy than traditional methods. By analyzing past market trends and relevant factors, these algorithms can identify patterns that contribute to future price movements.

The project's goal is to develop a robust predictive model that can effectively capture market complexities and provide reliable forecasts. Through techniques like time series analysis and regression, we aim to build a model adaptable to changing market conditions, empowering stakeholders with actionable insights.

## Dependencies

To run the scripts in this repository, the following libraries are required:
- numpy
- panda
- matplotlib
- Linear Regression
- Math

## Features
- *Linear Regression:* Utilizes the Linear Regression algorithm to predict the value of stock prices.
- *Training Data:* The training data is created using folders dedicated to different companies stock prices at a given time.
- *Accuracy:* Achieves high accuracy in stock value prediction.

## Linear Regression
Linear regression is a foundational statistical method used for modeling the relationship between a dependent variable and one or more independent variables. It's a simple yet powerful technique commonly employed for prediction and inference tasks across various fields, including finance, economics, healthcare, and social sciences.

At its core, linear regression aims to fit a linear equation to observed data points, enabling the estimation of the relationship between the independent variables (often referred to as features or predictors) and the dependent variable (often referred to as the target or outcome variable). This relationship is represented as:
y=β0+β1x1+β2x2+...+βnxn+ϵ
## Usage
1. Install dependencies using the provided requirements file.
2. Run the stock market prediction script, providing input csv files for analysis.
3. View the output results, including stocks predicted plots.

## Feature Extraction 
The data, specifically the 'Prev Close,high,close,volume' column representing the closing prices of the stock, undergoes normalization using the MinMaxScaler from scikit-learn. Normalization scales the values between 0 and 1, which is a common preprocessing step to ensure uniformity and enhance model convergence during training.

## Training Data 
The model is Trained by Giving the input as csv file of the companys data which include 'Closing price of stock','Highest Values','lowest Value','Volume' etc.
After trainning the data we have created a pickle file for the model for further Testing of the model.

![download](https://github.com/him200anshu/Stock_market_prediction/assets/107635981/f92a1995-3a34-4caa-a4a2-cd842acddcf3)


## Testing Data
The Model is Tested by giving the input as csv file of the companys data which include 'Closing price of stock','Highest Values','lowest Value','Volume' etc.
Here no need to create or train  the model in Raspberry pi it will predict the plots using the pickle file.

![HDFC](https://github.com/him200anshu/Stock_market_prediction/assets/107635981/d5aa13e5-4593-42d0-90cf-8bc328947204)
![KOTAK](https://github.com/him200anshu/Stock_market_prediction/assets/107635981/5f15d0c1-e8e6-44d2-ab4a-53c47e4ac129)
![GAIL](https://github.com/him200anshu/Stock_market_prediction/assets/107635981/0e5fda74-16d6-4a9c-aefd-6e7d8eeaae9a)




## Color Detection Demo Video

Watch a demo video 

https://www.youtube.com/watch?v=LmKoMUM5qOw





## Conclusion

The Stock Market Prediction Project showcases the effectiveness of linear regression in forecasting stock price movements. Leveraging historical data and machine learning techniques, our model demonstrates reasonable accuracy in predicting future stock prices. While linear regression serves as a strong baseline, its limitations must be considered, including its assumption of linear relationships and sensitivity to data quality. Nonetheless, this project highlights the potential of data-driven approaches to enhance decision-making in financial markets. Future endeavors may explore advanced algorithms and additional data sources for further improvements. Overall, our project contributes to advancing understanding and application of predictive modeling in navigating the complexities of stock market investing.
