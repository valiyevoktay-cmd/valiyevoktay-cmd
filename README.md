# Oktay Valiyev
**Quantitative Researcher & Data Engineer | Market Microstructure**

Incoming BSc International Economics student at Jönköping International Business School. My primary focus is on market microstructure, limit order book dynamics, and quantitative data engineering. I build event-driven infrastructure to analyze high-frequency market mechanics, utilizing vectorized data pipelines and Bayesian econometrics to quantify liquidity phase transitions.

---

## 🔬 Featured Quantitative Projects

### [Caspian Alpha](https://github.com/valiyevoktay-cmd/caspian-alpha-hft-microstructure-tracker)
> **Market Microstructure & Order Flow Imbalance Engine**

An institutional-grade, event-driven quantitative research environment designed to analyze Level 2 (L2) market microstructure dynamics in real-time. Built to ingest high-frequency WebSocket streams, calculate normalized liquidity anomalies, and execute empirical event studies.

* **Deterministic $O(1)$ State Machine:** Implements a highly optimized local order book reconstruction, avoiding CPU-heavy deep rescans during high-volatility tick bursts.
* **Multi-Factor Liquidity Analysis:** Tracks vectorized multi-level OFI, Order Book Imbalance (OBI), and calculates Z-scaled liquidity deltas to spot hidden divergences.
* **Adverse Selection Modeling:** Features a dedicated research slicer to empirically track "Liquidity Vacuums"—the exact moments market makers pull quotes prior to macroeconomic shocks.
* **Full-Stack Quant Architecture:** Containerized pipeline combining `asyncio`, WebSockets, and SQLite (WAL mode) with automated GitHub Actions CI/CD workflows.
  
### [Caspian Contagion](https://github.com/valiyevoktay-cmd/CaspianContagion)
> **Decoding Market Toxicity through Self-Exciting Processes**

An analytical engine engineered to detect and quantify microstructural phenomena in real-time cryptocurrency markets, specifically tracking Order Flow Imbalance (OFI) and utilizing continuous Hawkes processes to calculate the Contagion Condition Index (CCI).

* **High-Throughput Ingestion:** A persistent, thread-safe global bridge processing live Binance L2 WebSocket streams (`@depth20@100ms`) with minimal computational overhead.
* **Zero-Flicker HFT Terminal:** Institutional-grade UI achieving autonomous 1Hz rendering via static DOM anchoring and WebGL-accelerated Plotly charts, completely eliminating visual tearing.
* **Autonomous Risk Engine:** A protective Killswitch that halts virtual market-making operations when the CCI dictates extreme microstructural decay, preserving capital against informed traders.

### [Nordic Void](https://github.com/valiyevoktay-cmd/nordic_void_engine)
> **Event-Driven Infrastructure for High-Frequency Microstructure Research**

A specialized analytical engine designed for the millisecond-level quantification of liquidity vacuum events. The architecture executes vectorized processing of high-fidelity Top-of-Book tick data to isolate microstructural decay surrounding scheduled macroeconomic shocks.

* **Core Research Objective:** Maps the deterministic phase transition from baseline market resiliency to structural failure, identifying preemptive algorithmic liquidity withdrawal preceding Swedish Riksbank interest rate announcements.
* **Vectorized Architecture:** Avoids iterative loops to mitigate latency, relying on C-optimized backends for localized window calculations.
* **Transaction Cost Analysis (TCA):** Utilizes an empirically calibrated 5.3-sigma threshold ($Z > 5.3$) to isolate endogenous signals, calculating Top-of-Book Execution Penalty as a quoted shadow cost.
* **Inferential Framework:** Integrates Bayesian Markov Chain Monte Carlo (MCMC) methods, employing a Bayesian Beta-Binomial framework and a Gaussian Mixture Model (NUTS) to confirm the bimodal nature of market collapse.

---

## ⚙️ Core Technical Stack

* **Languages:** Python 3.10+ (Strictly Typed)
* **Quantitative & Math:** `numpy`, `pandas`, `scipy`, Bayesian Econometrics (MCMC)
* **Data Engineering:** `asyncio`, WebSockets, Event-Driven State Machines, SQLite (WAL Mode)
* **DevOps & Infrastructure:** Docker, GitHub Actions, `pytest`
* **Visualization:** WebGL, Plotly, Streamlit

---

## 🤝 Let's Connect

I am always open to connecting with fellow quantitative researchers, algorithmic traders, and data engineers. 

* **LinkedIn:** [Oktay Valiyev](https://www.linkedin.com/in/oktay-valiyev-336bb5401/?skipRedirect=true)
* **Academic Citation:** If utilizing the Nordic Void infrastructure for research, please cite the primary study: *Valiyev, O. (2026). The Riksbank Liquidity Vacuum: High-Frequency Evidence of Monetary Policy Transmission Friction.*

*Disclaimer: The software in my repositories is provided for research and academic purposes only. It does not constitute financial advice. High-frequency algorithm simulation involves significant risk and complexity.*
