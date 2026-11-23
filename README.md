# Mark Antar

Computer Engineering and Mathematics (Applied Mathematics) at the University of Illinois Urbana-Champaign · Business minor

I build quantitative research tools in Python and performance-focused systems in C++, with FPGA work in
SystemVerilog on the side. Interested in quantitative research, trading systems, and software engineering.

## Projects

### [lob-engine](https://github.com/kramarker/lob-engine) · C++20
Limit order book matching engine with price-time priority, integer-tick prices, partial fills, cancels, and
market / IOC / FOK orders. 26 GoogleTest cases run under ASan/UBSan in CI. Throughput benchmarks (Google
Benchmark) and per-operation latency percentiles from a TSC-based timing harness.

### [quant-trading-backtester](https://github.com/kramarker/quant-trading-backtester) · Python
Backtester for MA crossover, RSI, and Bollinger strategies on SPY, QQQ, and AAPL with next-day execution and
transaction costs. Includes walk-forward validation, a cross-asset generalization study with a short paper, and
a 28-test pytest suite.

### [quant-risk-simulator](https://github.com/kramarker/quant-risk-simulator) · Python
Monte Carlo engine comparing one-year VaR, CVaR, and drawdown distributions under Gaussian, Student-t,
stressed-volatility, and SPY block-bootstrap return models (5,000 paths per scenario).

## Tools

Python (pandas, NumPy, matplotlib, pytest) · C++20 (CMake, GoogleTest, Google Benchmark) · C · SystemVerilog · MATLAB · Git · Linux

## Contact

[LinkedIn](https://www.linkedin.com/in/-markantar) · markantar30@gmail.com
