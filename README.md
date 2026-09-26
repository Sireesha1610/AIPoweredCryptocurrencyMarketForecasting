# AIPoweredCryptocurrencyMarketForecasting
AI-powered hybrid framework for cryptocurrency market forecasting using Temporal Fusion Transformer (TFT), FinBERT sentiment analysis, and Soft Actor-Critic (SAC) reinforcement learning.

An AI-driven hybrid framework for **cryptocurrency market forecasting and trading strategy analysis**, combining **deep learning, NLP-based sentiment analysis, and reinforcement learning**.

## 🚀 Overview

This project integrates three complementary AI components:

* **Temporal Fusion Transformer (TFT)** — Forecasts cryptocurrency market trends from historical OHLCV and time-series data.
* **FinBERT** — Extracts financial sentiment from cryptocurrency-related news and social media data.
* **Soft Actor-Critic (SAC)** — Uses reinforcement learning to learn trading strategies based on market conditions and predicted signals.

The framework combines **market data and sentiment signals** to create a more comprehensive approach to cryptocurrency market analysis.

## 🧠 Technologies

**Python · Deep Learning · NLP · Reinforcement Learning · Time-Series Forecasting · FinBERT · TFT · SAC · Pandas · NumPy · PyTorch**

## 📊 Evaluation Metrics

The framework evaluates forecasting and trading performance using metrics such as:

* RMSE
* MAE
* Sharpe Ratio
* Sortino Ratio

## 🎯 Objective

To develop a hybrid AI framework that combines **price forecasting, financial sentiment analysis, and reinforcement learning** for data-driven cryptocurrency market analysis and trading strategy evaluation.

> **Note:** This project is developed for research and educational purposes and does not constitute financial advice.
> ## 🏗️ Architecture & Workflow

The proposed framework follows a multi-stage pipeline that integrates **market data, financial sentiment, deep learning, and reinforcement learning**.

```text
                  ┌─────────────────────────┐
                  │     Data Collection     │
                  └────────────┬────────────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
        ┌───────▼────────┐          ┌────────▼─────────┐
        │  Market Data   │          │ News & Social    │
        │    (OHLCV)     │          │ Media Data       │
        └───────┬────────┘          └────────┬─────────┘
                │                            │
        ┌───────▼────────┐          ┌────────▼─────────┐
        │ Preprocessing  │          │ Text Cleaning &  │
        │ & Feature Eng. │          │ Preprocessing    │
        └───────┬────────┘          └────────┬─────────┘
                │                            │
        ┌───────▼────────┐          ┌────────▼─────────┐
        │      TFT       │          │     FinBERT      │
        │ Time-Series    │          │ Sentiment        │
        │ Forecasting    │          │ Analysis         │
        └───────┬────────┘          └────────┬─────────┘
                │                            │
                └──────────────┬─────────────┘
                               │
                     ┌─────────▼─────────┐
                     │ Signal Integration│
                     │ Market + Sentiment│
                     └─────────┬─────────┘
                               │
                     ┌─────────▼─────────┐
                     │       SAC         │
                     │ Reinforcement     │
                     │ Learning Agent     │
                     └─────────┬─────────┘
                               │
                     ┌─────────▼─────────┐
                     │ Trading Strategy  │
                     │ & Decision Making │
                     └─────────┬─────────┘
                               │
                     ┌─────────▼─────────┐
                     │    Evaluation     │
                     │ RMSE • MAE        │
                     │ Sharpe • Sortino  │
                     └───────────────────┘
```

### 🔄 Workflow

1. **Data Collection**
   Historical cryptocurrency **OHLCV data** is collected along with relevant news and social media content.

2. **Data Preprocessing**
   Market data is cleaned and transformed into suitable time-series features, while textual data undergoes preprocessing before sentiment analysis.

3. **Market Forecasting — TFT**
   The **Temporal Fusion Transformer (TFT)** learns temporal patterns and relationships within market data to generate cryptocurrency price/trend forecasts.

4. **Sentiment Analysis — FinBERT**
   **FinBERT** analyzes financial text to extract positive, negative, or neutral sentiment signals from news and social media.

5. **Signal Integration**
   Forecasting outputs and sentiment signals are combined to provide a richer representation of the current and expected market conditions.

6. **Reinforcement Learning — SAC**
   The **Soft Actor-Critic (SAC)** agent interacts with the market environment and learns trading policies based on the integrated signals.

7. **Trading Strategy Evaluation**
   The resulting strategy is evaluated using both forecasting and risk-adjusted performance metrics, including **RMSE, MAE, Sharpe Ratio, and Sortino Ratio**.

### 🔗 End-to-End Pipeline

**Market Data + Sentiment Data → Preprocessing → TFT Forecasting + FinBERT Sentiment → Signal Fusion → SAC Agent → Trading Strategy → Performance Evaluation**


