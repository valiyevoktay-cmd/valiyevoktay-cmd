# OV
**Aspiring Quantitative Researcher & Data Engineer | Market Microstructure**

Build event-driven infrastructure to analyze high-frequency market mechanics — vectorized data pipelines, Bayesian econometric models, and real-time order book engines. My work focuses on quantifying liquidity phase transitions, adverse selection dynamics, and macro-shock transmission in FX and crypto markets.


---

## 🔬 Featured Projects

### [Caspian Alpha](https://github.com/valiyevoktay-cmd/caspian-alpha-hft-microstructure-tracker) — Market Microstructure & OFI Engine
> Event-driven research environment for real-time Level 2 order book analysis

- **O(1) State Machine:** Dictionary-based local L2 book reconstruction; ~55 µs end-to-end tick processing pipeline
- **Multi-Factor Liquidity Analysis:** Vectorized OFI, Order Book Imbalance (OBI), Z-score normalized anomaly detection
- **Adverse Selection Modeling:** Empirical event studies quantifying liquidity evaporation before macro shocks (25.6% depth drop at T−30s)
- **Full Stack:** `asyncio` WebSocket ingestion → SQLite WAL → Streamlit/Plotly dashboard; Docker + GitHub Actions CI/CD

---

### [Caspian Contagion](https://github.com/valiyevoktay-cmd/CaspianContagion) — Hawkes Process Toxicity Engine
> Detects self-exciting order flow contagion via MLE-calibrated Hawkes processes

- **Contagion Condition Index (CCI = α/β):** Killswitch triggers when CCI ≥ 1.0, halting virtual market-making against informed flow
- **O(N) Recursive Kernel:** $R(i) = e^{-\beta \Delta t}(1 + R(i-1))$ for efficient L-BFGS-B log-likelihood optimization
- **Zero-Flicker HFT Terminal:** `uirevision='constant'` + WebGL Plotly eliminates re-render tearing at 1Hz autonomous refresh

---

### [Nordic Void](https://github.com/valiyevoktay-cmd/nordic_void_engine) — FX Microstructure Research Engine
> Millisecond-level quantification of liquidity vacuums surrounding Riksbank & Norges Bank rate decisions

- **Research Result:** Mapped 5.3-sigma anomaly threshold isolating endogenous liquidity withdrawal preceding monetary policy events across EUR/SEK and EUR/NOK (2014–2026)
- **Bayesian Inference:** PyMC NUTS sampling, Beta-Binomial failure modeling, PSIS-LOO model selection via ArviZ
- **Transaction Cost Analysis:** IHS variance stabilization + shadow slippage cost in basis points

---

### [Baku Alternative CPI](https://github.com/valiyevoktay-cmd/baku-alternative-cpi) — Independent Inflation Tracker
> ETL pipeline computing alternative Laspeyres CPI from scraped Baku supermarket prices

- **Bottom-Up Methodology:** Daily BeautifulSoup4 scraper → SQLAlchemy ORM → Laspeyres Index engine → Streamlit dashboard
- **Divergence Analysis:** Surfaces gaps between real market-observed inflation and Central Bank of Azerbaijan's 4.0% target

---

## ⚙️ Core Technical Stack

| Domain | Technologies |
| :--- | :--- |
| Languages | Python 3.10+ (Strictly Typed) |
| Quantitative | `numpy`, `pandas`, `scipy`, PyMC, ArviZ, Bayesian MCMC |
| Data Engineering | `asyncio`, WebSockets, Event-Driven State Machines, SQLite WAL |
| DevOps | Docker, GitHub Actions, `pytest` |
| Visualization | WebGL, Plotly, Streamlit |

---

## 🤝 Let's Connect

- **Academic:** [SSRN Profile](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6771542)

*All repositories are provided for research and academic purposes only. High-frequency algorithm simulation involves significant risk and complexity.*
