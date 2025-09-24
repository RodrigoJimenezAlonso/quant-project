# Quant Project

End-to-end quantitative research pipeline:
- Data loading & cleaning
- Feature engineering (SMA/EMA/RSI/momentum/volatility)
- Signals & vectorized backtesting with costs
- Portfolio construction (equal-weight vs. max Sharpe)
- Risk management (leverage & beta-hedging)
- Evaluation (CAGR, Sharpe, Sortino, MaxDD) & efficient frontier

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
