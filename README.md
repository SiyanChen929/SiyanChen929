## Siyan (Diego) Chen

University of California, Santa Barbara · B.S. Applied Mathematics · B.S. Statistics & Data Science · B.A. Economics

**Research interests:** Quantitative Strategies, Factor Search, and Portfolio Optimization.

My research asks what information an investment decision really rests on, and whether more of it improves the decision. That means more search effort, more data, and more model capacity. I build research systems that measure this end to end: a candidate signal is judged by what survives chronological out-of-sample testing, transaction costs and multiple-testing control, not by how good it looks in training.

### Research

| Project | Question | Headline finding |
|---|---|---|
| [**StableAlpha**](https://github.com/SiyanChen929/stablealpha) · [paper](https://doi.org/10.5281/zenodo.23379471) | What is the marginal yield of extra LLM-guided search effort, and of extra information, in alpha-factor discovery? | More search raised the best training score by 16.9% while net annual return moved −0.24 pp: search gains do not transmit to returns, and information is worth more than search over it. |
| [**MarketIntel**](https://github.com/SiyanChen929/marketintel) | Can an always-on, auditable pipeline over filings, news and prices turn the AI-semiconductor value chain into an investable, explainable signal? | Processed 36,384 news items, press releases and filings in three weeks; growth acceleration, not value, carries the point-in-time signal, and risk budgeting matters more than the optimizer. |
| [**MSCI Rebalance Event Study**](https://github.com/SiyanChen929/msci-rebalance-event-study) | Where does index-inclusion price pressure live in the closing auction, and how much of it survives multiple-testing correction? | Isolates a 13.5 bp-per-review event-minute effect and shows how a state gate lifts the hit rate from 70.6% to 87.5%. |
| [**Alpha Engine**](https://github.com/SiyanChen929/alpha-engine) | Which monthly US-equity signals (momentum, ML overlays, SEC 8-K and Form 4 events) clear preregistered statistical gates? | Diversified momentum reaches Sharpe 1.23; the ML overlay and SEC event drift are rejected on evidence by a preregistered decision rule. |
| [**US Equity Pairs**](https://github.com/SiyanChen929/us-equity-pairs) | Do classic within-sector pairs-trading edges in the S&P 500 survive realistic costs? | Across 13,917 candidate pairs the broad edge is gone after costs; a selection-bias null shows a +12.4% "best ten" curve is an order statistic, not alpha. |
| [**China Commodity Pairs**](https://github.com/SiyanChen929/china-commodity-pairs) | Do cointegrated futures spreads within Chinese industrial chains (rebar–iron ore and beyond) hold up out of sample? | Within-chain pairs earn a held-out Sharpe of 1.06; the same test over all 1,225 cross-chain pairs finds nothing, so industry structure is the source of the signal. |
| [**Agri Macro Monitor**](https://github.com/SiyanChen929/agri-macro-monitor) | Do USDA supply–demand balance sheets and weather predict grain futures returns, using only point-in-time information? | WASDE revisions inform wheat specifically; the locked model holds a +1.49% out-of-sample R² and a net Sharpe of 0.71. |

### Papers

- **Chen, S. (2026).** *The Marginal Yield of LLM-Guided Alpha Search: Search Effort, Information and Investment Value.* Working paper, Zenodo. [doi:10.5281/zenodo.23379471](https://doi.org/10.5281/zenodo.23379471)
- **Chen, S. (2025).** *Momentum-Driven Mean-Variance Optimization Strategy for Large-Cap U.S. Stocks.* Advances in Economics, Management and Political Sciences, 200, 229–238. [doi:10.54254/2754-1169/2025.LH25530](https://doi.org/10.54254/2754-1169/2025.LH25530)

### Toolkit

Python (pandas, NumPy, scikit-learn, statsmodels, LightGBM, Optuna), R, SQL, SAS · statistical learning, time-series econometrics, portfolio optimization, event studies, cost-aware backtesting, reproducible research pipelines.

### Contact

[siyan_chen@ucsb.edu](mailto:siyan_chen@ucsb.edu) · [LinkedIn](https://www.linkedin.com/in/siyan-chen-75b9082ab/)
