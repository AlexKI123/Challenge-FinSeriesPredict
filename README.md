# Financial Time Series Prediction: Optimal Learning Rate and Model Architecture Exploration

This repository presents a comprehensive exploration of machine learning techniques for predicting financial market trends, developed as part of an online challenge hosted by [Challenge Data](https://challengedata.ens.fr). It contains a series of analytical notebooks and scripts designed to optimize the performance of predictive models through systematic experimentation and tuning. The datasets used for model training and validation are sourced from the challenge, providing a rich basis for applying and evaluating advanced machine learning strategies in the context of financial data.

## Key Components

### [Exploratory Data Analysis (EDA)](DataExploration.ipynb)
The repository includes an EDA notebook that guides the initial investigation of the financial time series data. This notebook covers data visualization, statistical summaries, and preliminary analysis, laying the groundwork for informed model development and hypothesis generation.


### [Optimal Learning Rate Finder](LearningRateFinder.ipynb)
A Python notebook implementing a Learning Rate Finder to identify the most effective learning rate for training deep learning models. This facilitates the selection of a learning rate that balances the convergence speed and stability of the model training process.

### [Model Architecture Optimization with KerasTuner](KerasTuner.ipynb)                          
Utilizes KerasTuner to automate the search for the optimal neural network architecture. Evaluates various configurations to identify the structure offering the best prediction accuracy.

### Predictive Modeling with XGBoost
Demonstrates the application of the XGBoost framework to financial time series prediction.

### LSTM-Based Time Series Forecasting
Explores the use of Long Short-Term Memory (LSTM) networks for predicting market conditions, including steps for data preprocessing, model construction, training, and evaluation.

## Dataset and Challenge Context

The data utilized in this project is derived from an online challenge available at [Challenge Data](https://challengedata.ens.fr), focusing on financial market trends prediction. Participants are encouraged to develop innovative machine learning solutions to predict future market conditions based on historical data. For more information on the dataset and challenge rules, visit the challenge website.

