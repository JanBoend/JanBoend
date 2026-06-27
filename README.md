## Systematic trading researcher

I build backtesting infrastructure, quantitative strategies, and the tools to research and deploy them.
Currently running a 10-strategy live portfolio on IC Markets via cTrader.

---

### Strategy performance

| Strategy | Sharpe | Ann return | Max drawdown | Period |
|---|---|---|---|---|
| 10-strategy portfolio | 4.16 | 110% (2% risk) | -7.49% | 2020–2025 |
| AMD – EURUSD | 1.40 | 16.45% | -5.01% | 2019–2025 |
| AMD – QQQ | 1.36 | 19.74% | -8.2% | 2019–2025 |
| iFVG – EURUSD | 1.80 | — | — | 2021–2025 |
| ORB – QQQ | 1.14 | 12.93% | -7.56% | 2019–2025 |

Walk-forward validated: 13–15/16 out-of-sample windows profitable per strategy.
2022 bear market: AMD strategy +45.91% while QQQ fell -32%.

![Portfolio equity curve](equity_curve.png)

---

### Projects

| Repo | Description |
|---|---|
| [quant-engine](https://github.com/Soakedape/quant-engine) | Vectorised backtesting engine — 2100 lines of original infrastructure |
| [icm-strategies](https://github.com/Soakedape/icm-strategies) | 10 ICT-based strategies across equities and FX, walk-forward validated |
| [algoforge](https://github.com/Soakedape/algoforge) | AI strategy lab — plain English → backtest via Claude API |
| [live-dashboard](https://github.com/Soakedape/live-dashboard) | Flask trade dashboard + SQLite trade logger |
| [options-pricer](https://github.com/Soakedape/options-pricer) | Black-Scholes + Monte Carlo pricer, Greeks, IV solver, web UI |
| [portfolio-optimizer](https://github.com/Soakedape/portfolio-optimizer) | Markowitz vs grid search — efficient frontier and production allocation |
| [market-regime-detector](https://github.com/Soakedape/market-regime-detector) | HMM regime classifier — bull / bear / sideways |
| [factor-backtest](https://github.com/Soakedape/factor-backtest) | Fama-French 3-factor attribution — alpha vs beta decomposition |

---

**Stack:** Python · pandas · numpy · scipy · Flask · SQLite · hmmlearn · Claude API · cTrader (live)
