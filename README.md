# maybank-lstm-stock-prediction

Stock price prediction for Maybank (1155.KL) using LSTM with attention mechanism and technical indicators (RSI, MACD).

![Maybank LSTM Banner](https://github.com/Tahanijabir/maybank-lstm-stock-prediction/blob/main/animationmaybank%20(1).jpg?raw=true)

---

##  Project Overview

This repository presents a deep learning approach for forecasting stock prices of **Maybank** (Bursa Malaysia: `1155.KL`), Malaysia’s largest bank. The model leverages a hybrid architecture combining **Long Short-Term Memory (LSTM)** networks and an **attention mechanism** to better capture temporal dependencies and highlight significant patterns in the time series data.

To enrich predictive performance, the model integrates commonly used **technical indicators** such as **Relative Strength Index (RSI)**, **MACD**, and **Moving Averages**, providing contextual market signals alongside raw price data.

---

##  Model Architecture

The forecasting model is composed of the following layers and concepts:

- **LSTM layers** to capture sequential dependencies and memory across time steps.
- An **attention mechanism** to dynamically weigh relevant time points during training, improving interpretability and prediction accuracy.
- Trained on 70% of historical daily price data and evaluated on the remaining 30% test set.

This setup enables the model to learn both short-term and long-term trends and outperform naïve baselines.

---

##  Technical Indicators Included

To mimic real-world financial analysis, the dataset was enriched with key indicators:

- **RSI (Relative Strength Index)** : reflects overbought/oversold conditions.
- **MACD (Moving Average Convergence Divergence)** : captures momentum shifts.
- **Moving Averages (MA100, MA200)** : smooth trends for long-term signal tracking.
![RSI](https://github.com/Tahanijabir/maybank-lstm-stock-prediction/blob/main/RSI.png?raw=true)
![MACD](https://github.com/Tahanijabir/maybank-lstm-stock-prediction/blob/main/MACD.png?raw=true)
![Moving Averages](https://github.com/Tahanijabir/maybank-lstm-stock-prediction/blob/main/indicators.png?raw=true)
These indicators help the model learn market behavior beyond raw price fluctuations.

---

##  Technology Stack

This project was implemented in Python using the following libraries:

- **Data acquisition & manipulation**: `yfinance`, `pandas`
- **Visualization**: `matplotlib`
- **Modeling & preprocessing**: `scikit-learn`, `TensorFlow`/`Keras`
- **Notebook environment**: Jupyter

---

##  How to Run the Notebook

Ensure you have Python installed, then run:

```bash
pip install yfinance pandas matplotlib scikit-learn tensorflow


