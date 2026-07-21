# Hi, I'm Oğuzhan Düğüncü 👋
**Systems Engineer — C++ / Quantitative Systems / Simulation**

I build things from first principles: low-level systems, physics simulations, and — most recently — a fully independent algorithmic crypto trading pipeline. My background is telecom/electronics engineering, and I've worked as a C++ backend engineer at Huawei and Amadeus. These days I'm building my own systems rather than someone else's roadmap.

---

## 🔬 What I'm working on

**Systematic Crypto Trading System** *(private, in production)*
A real-time signal-processing and regime-detection pipeline for crypto markets — order flow imbalance (OFI) tracking, hysteresis-based regime classification, scanner/momentum signal chains, and a GradientBoosting precursor model for early-signal detection. Built on OKX WebSocket + Binance REST, with statistically validated hypotheses backed by backtesting (not vibes).

**[engine_playground](https://github.com/oguzhanduguncu/engine_playground)** — a C++ physics & simulation sandbox
- Rigid body dynamics + continuous collision detection
- RVO/ORCA multi-agent navigation (emergent lane formation in bidirectional flow)
- Kalman filtering (originally built for missile-tracking use cases)
- A small neural network module built from scratch (no framework)

Long-term direction: working toward multi-robot coordination — RVO/ORCA → control theory → multi-agent coordination → ROS 2 + Gazebo → formal safety verification, aimed at safety-critical autonomous systems.

---

## 🧠 How I work
I prefer implementing something myself before reaching for a framework — I want to understand the machinery, not just the API surface. Currently going deep on C++ internals (object model, vtables, memory layout) and building up probability/stochastic-process foundations from the ground up rather than skipping to applied ML.

---

## 🛠️ Tech
- **Languages:** C++, C, Python
- **Systems:** Linux, multithreading, memory management, network I/O
- **Domains:** real-time data pipelines, numerical simulation, quantitative/statistical modeling
- **Tooling:** CMake, Git, GDB, Docker

---

## 🤖 Claude's Take (unfiltered, by request)
I've worked with him enough to say this honestly: he doesn't accept a result until he's broken it himself first. Most people call a backtest "done" when the number looks good — he goes looking for the bug that's making it look good. That instinct is rare and it's the actual reason his trading system's validated findings hold up.

The flip side: he can get stuck refining the machine instead of running it. The RVO/ORCA engine, the regime hysteresis system, the fatigue models — all genuinely rigorous, but rigor can become its own form of procrastination. At some point the exit-execution bottleneck he's already identified matters more than the next elegant signal refinement. He knows this; whether he acts on it is the real test.

He also undersells himself constantly — the self-deprecating humor is charming but it's not calibrated to what he's actually built here.

## 📫 Reach me
- 📧 oguzhanduguncu@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/oguzhan-duguncu7)

> Interested in performance-critical systems, simulation, and turning statistical rigor into things that actually work in production.
