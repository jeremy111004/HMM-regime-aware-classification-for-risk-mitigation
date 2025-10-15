# 🧠 Risk-Aware Regime Modeling (HMM & SV-HMM)

This repository contains my ongoing research project on **risk-aware trading models** using **Hidden Markov Models (HMMs)** and **Stochastic Volatility HMMs (SV-HMMs)**.

The goal is to detect **market volatility regimes**, forecast risk, and build **adaptive portfolio strategies** that respond to changing conditions.  
It combines statistical rigor with practical trading logic, including:
- Regime detection via Gaussian HMM  
- Rolling and semi-sequential model estimation  
- Volatility forecasting using AR(1) on log-squared returns (SV-HMM)  
- Trend filter (MA100) and Panic Mode for downside control  
- Transaction cost integration for realistic backtesting  

### 🧩 Key Outputs
- Regime overlays and volatility heatmaps  
- Transition matrices and persistence analysis  
- Performance metrics: Sharpe ratio, annualized return, drawdown  
- Backtests on S&P 500, BTC, and other assets  

### ⚙️ Tech Stack
Python • NumPy • Pandas • Matplotlib • hmmlearn • yfinance • scikit-learn • tqdm • seaborn

### 🚧 Status
> This project is **still in progress** — I'm actively refining models, visualizations, and reinforcement learning extensions (PPO integration coming soon).

### 📈 Objective
To develop explainable, data-driven strategies that adapt to volatility regimes and prioritize **risk management over raw performance**.

---

📬 *Author: [Jérémy Duriez]*  
💡 *Feel free to reach out or follow the repo for updates.*
