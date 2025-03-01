# NTU Deep Learning Week 2025

## Team Lean Large Men - AI-Powered Trading Strategy (Finance Track)

This repository contains the submission by **Team Lean Large Men** for the **NTU Deep Learning Week 2025** competition, held from **February 28, 2025, to March 3, 2025**. Our project explores AI-driven trading strategies, leveraging **deep reinforcement learning (DQN)** and **LSTM-Transformer models** to analyze and predict financial market movements.

---

## 🚀 Project Overview

Our work critically examines the challenges of algorithmic trading, acknowledging the complexities of financial markets where statistical relationships are constantly shifting. While outperforming institutional-grade quantitative firms remains unrealistic, our approach provides valuable insights into the application of deep learning in financial modeling.

### 🔹 Implemented AI Strategies
- **LSTM-Transformer Hybrid Model**: Designed for price prediction, capturing both short-term and long-term dependencies in market data.
- **Deep Q-Network (DQN) Reinforcement Learning Agent**: An adaptive trading strategy that learns from market conditions to optimize decision-making.

### 📊 Key Features & Indicators
To enhance model robustness, we incorporated macroeconomic and technical indicators such as:
- Moving Averages (50/200-day relationships)
- RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence)
- Bollinger Bands
- Federal Interest Rates
- Global Liquidity Measures (M1/M2 Money Supply)
- US Dollar Strength Index

---

## 📁 Repository Structure

### 📜 Main Files
- **`DL Week'25 Finance Track Report - Lean Large Men.pdf`** - Full project report detailing methodology, implementation, and results.
- **`LeanLargeMen_DLWeek2025.pptx`** - Presentation slides summarizing the project.
- **`Deep RL approach.ipynb`** - Implementation of the Deep Q-Network (DQN) reinforcement learning model.
- **`LSTM approach.ipynb`** - Implementation of the LSTM-Transformer hybrid model for price prediction.

### 📂 Datasets
- **`SPY_indicators.csv`** - Historical SPY price data with calculated technical indicators.
- **`fedIR.csv`** - Historical US Federal Reserve interest rates data.
- **`m1m2.xlsx`** - Historical data of M1 and M2 money supply measures.
- **`usdstrength.csv`** - US Dollar Index dataset tracking its strength against a basket of foreign currencies.
- **`final_df.csv`** - Merged dataset integrating all relevant macroeconomic and market indicators.

### 🔧 Additional Resources
- **`alphaVantage_marketSentiments.ipynb`** - API query implementation using AlphaVantage's market sentiment data.

---

## 🙌 Acknowledgments
We extend our gratitude to **NTU Deep Learning Week 2025** organizers and mentors for providing a platform to explore AI in trading. This project was a valuable learning experience in financial modeling, deep learning, and reinforcement learning applications.

For any inquiries or discussions, feel free to **open an issue** or **contact us through this repository**!

---

📢 _Happy Coding & Trading!_ 🚀
