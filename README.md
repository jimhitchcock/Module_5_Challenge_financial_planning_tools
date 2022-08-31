# Financial Planning with APIs and Simulations

*Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

*Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Module_5_Challenge_financial_planning_tools

This is the Module 5 challenge for the GWU FinTech Bootcamp

---

## Technologies

[Pandas](https://pandas.pydata.org/)

[%matplotlib inline](https://matplotlib.org/)

[json](https://docs.python.org/3/library/json.html)

[alpaca_trade_api](https://pypi.org/project/alpaca-trade-api/)

[MCSimulation](https://pbpython.com/monte-carlo.html)

[dotenv](https://pypi.org/project/python-dotenv/)

[requests](https://realpython.com/python-requests/)

---

## Installation Guide

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline
```
---

## Contributors

Parts of this application were written by Jim Hitchcock, starter code provided by GWU FinTech Bootcamp.
Further review and debugging provided by AskBCS help desk.

---

## License

MIT License