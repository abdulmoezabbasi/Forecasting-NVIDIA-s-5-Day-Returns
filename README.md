# Forecasting-NVIDIA-s-5-Day-Returns

This notebook builds a complete machine learning forecasting pipeline on 7,079 trading days of that record. The target variable is the 5-day forward return: given today's conditions, what percentage gain or loss will the stock produce over the next five trading days? This is a more practically useful question than predicting a raw price level, because returns are stationary, comparable across time, and directly actionable in a portfolio context.

The workflow covers ten analytical stages: data exploration, time-series decomposition, feature engineering, a classical ARIMA baseline, gradient boosting forecasting, time-series cross-validation, evaluation, feature importance, anomaly detection, and scenario simulation under two macroeconomic stress cases.

Dataset: NVIDIA Stock Data 1999 to 2026, covering 7,079 trading days across 16 columns including OHLCV prices, moving averages, RSI, quarterly revenue, market cap, stock split dates, and era labels.
