# Google-Stock-Price-Prediction
Leveraging Long Short-Term Memory (LSTM) neural networks, we forecast Google stock prices for January 2021. Our model utilizes 5-year historical data (2016-2020) and is evaluated on the test set for accurate predictions.

**Executive Summary**

This report presents the findings of our stock price prediction model for Google's stock prices in January 2021. The goal of this project was to develop a machine learning model using Long Short-Term Memory (LSTM) neural networks to forecast future stock prices based on historical data.

**Introduction**

In Quantitative finance, predicting stock prices with high accuracy is a crucial and challenging task. While it is impossible to precisely estimate stock prices, it is possible to make accurate predictions by using past stock prices, leveraging the theory behind Brownian Motions. By analyzing past upward and downward trends, we can use this information as an indicator to predict future prices. Long Short-Term Memory (LSTM) is a more sophisticated version of Recurrent Neural Networks (RNN) that addresses the Vanishing Gradient Problem often encountered in RNNs.

For this project, we used the past 5 years of Google stock price data from the time period 2016-2020. The primary objective is to predict the upward or downward trend in Google's stock price for January 2021.
![image](https://github.com/DivZyzz/Google-Stock-Price-Prediction/assets/136096930/6aefb9d4-5ef8-4d47-9e3e-6e3aa1476011)
**Methodology**

The project was carried out in the following steps:

1.Importing the Google stock price data for the time period 2016-2020.

2. Performing Data Normalization and Data Transformation to prepare the train and test sets.

3. Modelling the LSTM model and initializing the model parameters.

4. Training the Model and using the trained information to predict       the future stock price for January 2021.

5. Using the available Test Set data for evaluating the predictions.

**Result**

The LSTM model, based on 5 LSTMs, was able to predict the upward and downward trends in the stock prices effectively. As shown in the graph below, the red line corresponding to the predicted stock prices follows the same pattern as the blue line representing the real stock prices for the first month of 2021.

<img width="302" alt="image" src="https://github.com/DivZyzz/Google-Stock-Price-Prediction/assets/136096930/6672748c-d210-4492-9586-aebfc5b10855">

**Conclusion**

In conclusion, our LSTM-based stock price prediction model demonstrates potential for forecasting future stock prices based on historical data. While we achieved promising results, it is important to acknowledge the inherent uncertainty in stock price prediction due to the influence of various market factors. Stock price prediction remains a challenging task, and the model's accuracy may vary depending on market conditions and unforeseen events.


