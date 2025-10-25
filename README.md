## CryPe 1.0 — Cryptocurrency Price Prediction (Time-Series Forecasting)

CryPe 1.0 is the foundation stage of an intelligent crypto-forecasting system designed to predict cryptocurrency price movements using deep learning–based time-series models.
Currently, it is a base model that applies XGBoost, LSTM, and a pre-trained N-BEATS model on historical market data enhanced with engineered features such as moving averages and volatility indicators — achieving robust short-term predictive accuracy.

The name CryPe comes from Crypto + Prediction.
It started as a crypto prediction tool I built for myself, but as the vision evolved, I decided to expand it to analyze stocks and other financial sectors as well.
The indicators used are the same ones I personally apply for technical analysis in trading.

## Features

Built multivariate datasets including returns, SMA, and volatility

Using crucial indicators like MACD , Bolinger Bands , SMA , OBV , Relative Strength index that depicts real time analysis

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


git clone https://github.com/manveersingh1048/CryPe-1.0.git
cd CryPe-1.0
pip install -r requirements.txt

