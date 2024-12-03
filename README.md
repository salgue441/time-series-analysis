# 📊 Time Series Forecasting Models

## 🌟 Project Overview

This project provides a comprehensive toolkit for advanced time series forecasting, leveraging state-of-the-art techniques including SARIMA and LSTM models. Designed for data scientists and financial analysts, the toolkit offers robust model selection, performance evaluation, and visualization capabilities.

## ✨ Key Features

- 🔍 Automated SARIMA Order Selection
- 📈 Multiple Forecasting Model Comparison
- 🧮 Performance Metrics Calculation
- 🖼️ Intuitive Visualization
- 🚀 Parallel Processing Optimization

## 📦 Installation

```bash
git clone https://github.com/salgue441/time-series-analysis.git

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

## 🔬 Methodology

### SARIMA Order Selection

- Grid search across multiple parameter combinations
- Parallel processing for computational efficiency
- AIC (Akaike Information Criterion) for model selection

### LSTM Model

- Long Short-Term Memory (LSTM) architecture
- Hyperparameter tuning with RandomizedSearchCV
- Early stopping to prevent overfitting

### Performance Metrics

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
