# Quant Project — Systematic Strategy Research

This repository contains a complete, reproducible pipeline for designing, testing, and analyzing systematic trading strategies.  
It provides a structured workflow from data acquisition to reporting and is intended as a practical template for quantitative research.

---

## Overview

The objective of this project is to construct, evaluate, and document a rules-based trading strategy applied to a set of equities (e.g., AAPL, MSFT, AMZN, GOOG), and compare its performance to a benchmark index.

The workflow covers:

- Data collection and alignment
- Feature engineering (SMA, EMA, momentum, RSI, volatility)
- Signal generation (rule-based long/short logic)
- Portfolio construction (weights, normalization, rebalancing, transaction costs)
- Backtesting and performance evaluation
- Parameter optimization with train/test split
- Robustness checks (cost sensitivity, volatility targeting)
- Reporting and reproducibility (saved metrics, plots, CLI runner)

---

## Repository Structure

```text
quant-project/
├── notebooks/
│   └── QuantProject.ipynb        # Main research notebook
├── src/                          # Reusable modules
│   ├── io.py                     # Data loading and alignment
│   ├── features.py               # Feature engineering functions
│   ├── backtest.py               # Backtesting engine
│   └── metrics.py                # Performance metrics
├── reports/                      # Generated reports and CSV results
│   └── summary.md
├── figures/                      # Generated plots (equity, drawdown, Monte Carlo)
├── run_experiment.py             # CLI tool for quick re-runs
├── requirements.txt              # Python dependencies
└── README.md
