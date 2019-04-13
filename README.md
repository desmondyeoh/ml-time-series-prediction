# Machine Learning - Time Series Prediction
This repository presents the exploration of various machine learning techniques to do time series prediction.

## In this repository:

### Dataset
1. A univariate time-series data: `daily-total-female-births.csv`

### Jupyter Notebooks
1. Lesson 01 - Promise of Deep Learning
2. Lesson 02 - How to Transform Data for Time Series
3. Lesson 03 - MLP for Time Series Forecasting
4. Lesson 04 - CNN for Time Series Forecasting
5. Lesson 05 - LSTM for Time Series Forecasting
6. Lesson 06 - CNN-LSTM for Time Series Forecasting
7. Lesson 07 - Encoder-Decoder LSTM Multi-step Forecasting
8. Experiment on Random Forest Regressor

### Findings
I find that MLP with moving window pre-processing works the best for this simple univariate time series task. It achieves MSE (Mean Squared Error) of 50-53, which is amongst the best of all other methods. The results follows the work by Felix A. Gres et. all (2001) [[springer link]](https://link.springer.com/chapter/10.1007/3-540-44668-0_93) which suggested that LSTM should only be used for cases where traditional methods fail.

Reference: [[blog post in machinelearningmastery.com]](https://machinelearningmastery.com/how-to-get-started-with-deep-learning-for-time-series-forecasting-7-day-mini-course/)
