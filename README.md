## CryPe 1.0 — Cryptocurrency Price Prediction (Time-Series Forecasting)

CryPe 1.0 is the foundation stage of an intelligent crypto-forecasting system designed to predict cryptocurrency price movements using deep learning–based time-series models.Currently it is a base model that applies deep leanring models like XGBoost ,LSTM and pretrained model N-BEATS to historical market data enhanced with engineered features such as moving averages and volatility indicators, achieving robust short-term predictive accuracy.

## Features

Built multivariate datasets including returns, SMA, and volatility

Implemented sequence generation for sliding-window forecasting

Trained and compared LSTM and N-BEATS models using the Darts framework

Evaluated models with MAPE, RMSE, and visual trend overlays

Produced interpretable prediction plots for real-world insight

## Key Highlights

Feature Engineering: Extracted short- and long-term statistical signals (SMA, volatility, momentum)

Modeling: Leveraged LSTMModel and NBEATSModel from Darts for high-accuracy forecasts

Performance: Achieved MAPE ≈ 4.7 %, confirming strong predictive power on unseen data

Scalability: Modular design allows easy expansion for upcoming sentiment and vision modules

## Tech Stack

Language: Python 3.13

Libraries: Pandas | NumPy | Matplotlib | Scikit-Learn | Torch | Darts

IDE: VS Code / Jupyter Notebook

## Results

MAPE: 4.70 %

RMSE: Low deviation between predictions and actuals

Models effectively captured reversal and recovery phases in crypto trends

## Roadmap
Version	Focus	Description

CryPe 2.0	: NLP & Sentiment Analysis	Integrate financial-news and social-media sentiment features for improved predictive context

CryPe 3.0	: Computer Vision Analytics	Add CNN-based stock-chart pattern recognition and visual trend detection

CryPe Final	: AI Market Intelligence Platform	Unified system that evaluates undervalued assets, analyzes industry reports, and predicts macro-economic shifts


Author
Manveer Singh
Data Scientist | Machine Learning & AI Enthusiast
mssandhuu05@gmail.com




