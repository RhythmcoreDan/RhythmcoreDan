# Hi, I'm Dan 👋  
**Python Algo Engineer | System Architect | Creator of RhythmCore**

I build full-stack algorithmic trading systems using clean, modular, and testable Python architecture.  
Every component is designed to function independently — indicators, regimes, signals, execution, backtesting, and risk — all connecting into a cohesive engine.

---

## 🧠 What I Build
- **Custom Indicators**  
  Emotional/behavioral engines, volatility tools, wick/trend composites.

- **Market Regime Models**  
  Trend vs chop classification, volatility state mapping, regime grids.

- **Strategy & Signal Logic**  
  Modular decision systems built for clarity, testing, and extension.

- **Execution Engines**  
  Position tracking, order logic, PnL models, exposure handling.

- **Backtesting Systems**  
  Equity curves, performance metrics, drawdowns, trade stats.

- **Risk Management Layers**  
  Sizing, exposure limits, volatility filters, kill switches.

---

## 🔧 Modular Trading System Demos (Core Repos)

### 1. **[rhythmcore-demo-bot](https://github.com/RhythmcoreDan/rhythmcore-demo-bot)**  
Strategy structure + signal engine + backtesting loop.

### 2. **[emo-index-demo](https://github.com/RhythmcoreDan/emo-index-demo)**  
Emotional/behavior indicator using volatility, wick ratios, and composites.

### 3. **[regime-map-demo](https://github.com/RhythmcoreDan/regime-map-demo)**  
Market regime classifier (trend vs chop, high/low volatility).

### 4. **[execution-engine-demo](https://github.com/RhythmcoreDan/execution-engine-demo)**  
Position management, realized/unrealized PnL, and equity tracking.

### 5. **[backtester-demo](https://github.com/RhythmcoreDan/backtester-demo)**  
Backtesting engine generating equity curves and core performance metrics.

### 6. **[risk-manager-demo](https://github.com/RhythmcoreDan/risk-manager-demo)**  
Risk module controlling per-trade risk, exposure caps, volatility filters, and kill-switch logic.

---

## ⚙️ RhythmCore Architecture (High-Level)

                        +-----------------------------+
                        |         MARKET DATA         |
                        +-----------------------------+
                                      |
              +-----------------------+-----------------------+
              |                                               |
       +-------------+                                 +--------------+
       |  EMO ENGINE |                                 | REGIME ENGINE|
       +-------------+                                 +--------------+
              |                                               |
              +-----------------------+-----------------------+
                                      |
                            +------------------+
                            |  SIGNAL ENGINE   |
                            +------------------+
                                      |
                     +----------------+----------------+
                     |                                 |
            +-------------------+             +-------------------+
            | EXECUTION ENGINE  |             |  RISK MANAGER     |
            +-------------------+             +-------------------+
                     |                                 |
                     +----------------+----------------+
                                      |
                             +-------------------+
                             |    BACKTESTER     |
                             +-------------------+
                                      |
                             +-------------------+
                             | EQUITY & METRICS  |
                             +-------------------+


---

## 🧭 Engineering Philosophy  
Build systems like industrial machinery:

- Modular  
- Predictable  
- Maintainable  
- Extensible  
- Testable  

**Small components → Large systems.  
Clear logic → Scalable architecture.**

---

## 📬 Contact  
Open to collaboration, custom indicators, bot builds, and full system architecture work.  
Always building. Always refining.
