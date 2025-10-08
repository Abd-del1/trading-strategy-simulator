# Trading Strategy Simulator Project

This repository contains a Python-based trading strategy simulator that can be used to research, test and evaluate systematic trading ideas on historical market data.  It is aimed at learners and practitioners who want hands‑on exposure to the entire workflow of algorithmic trading: data collection, signal generation, backtesting, risk‑adjusted performance evaluation and portfolio construction.

## What’s included

- **`Trading_Strategy_Simulator.ipynb`** – an interactive Jupyter notebook that walks through the process of fetching price data, calculating trading signals, running backtests with transaction costs and slippage, computing a suite of performance metrics and exploring parameter variations.  The notebook uses a moving‑average crossover strategy and an RSI‑based strategy as examples.  A synthetic data fallback is provided if market data cannot be downloaded.
- **`requirements.txt`** – a list of Python packages used by the notebook.  Install them in a virtual environment with `pip install -r requirements.txt`.

## Getting started

1. **Install dependencies**

   Ensure you have Python 3.8+ installed.  Create a virtual environment and install the required packages:

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

2. **Run the notebook**

   Launch Jupyter and open the notebook:

   ```bash
   jupyter notebook Trading_Strategy_Simulator.ipynb
   ```

3. **Explore and modify**

   - Adjust the list of tickers and date ranges in the data fetching section.
   - Tweak the parameters of the moving‑average and RSI strategies.
   - Extend the backtester to include your own signal definitions, position sizing, or risk management rules.
   - Use the grid‑search section to compare different parameter combinations.
   - Build on the multi‑asset example to construct more sophisticated portfolios.

## Notes

This project does **not** execute live trades or connect to brokerage accounts.  It is intended for educational and research purposes.  If you wish to deploy live trading systems, please understand the risks and consult appropriate resources.

## License

This code is provided for educational purposes without warranty.  You may use, modify and distribute it under the terms of the MIT license.