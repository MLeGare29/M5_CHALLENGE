# FINANCIAL PLANNING ANALYSIS & PROJECTIONS

As requested, per our agreement with the Credit Union, in this repository is the code for the analysis and projections of their retirement fund: In this comprehensive breakdown will achieve two goals:

1. Assess the monthly budgets of our clients - visualizing their current savings, and based on the viability of their portfolio, determine if they have sufficient reserves to add an emergency fund to their retirement plan.

2. Use the Monte Carlo forecasting algorithm to run 500 simulations over the two given periods of 10 & 30 years, using an 80/20 and 60/40 weighted ratio, respectively, to project their retirement plan potential based on the current assets within their portfolio. 

The ultimate goal of this state of the art prototype application is to demonstrate and determine the best course of action for members of the Credit Union when this technology is rolled out to them. Using the Alpaca API technology, we will be able to achieve this goal using real-time data!


## TECHNOLOGIES

In order for this highly complex and technical application to run, there are installation requirements. They are the following:

[Python](https://www.python.org/downloads/) - Enables the user to use the powerful Python programming language.

[JupyterLab](https://jupyter.org/) - Access to the web-based IDE JupyterLab.  

[Pandas](https://pandas.pydata.org/) - Grants access to the open-source Pandas data analysis tool, which is powered by Python.

[Alpaca API & Secret Keys](https://alpaca.markets/) - Enables the user to access live stock and crypto trading data using their personal API & Secret Keys.


## USAGE

In order to execute, plot, and simulate this code, you must run the following:

Accessing JupyterLab in Bash: `Jupyter Lab`

```python
financial_planning_tools.ipynb
MCForecastTools.py
import pandas as pd
import os
import requests
import json
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline
```

![MC_30_line_plot](https://user-images.githubusercontent.com/127421460/236598604-df2f4bce-73c7-4913-98c2-186641b547a8.png)


## LINKS
The following links were used to access free live data for the BTC and ETH crypto currencies:

[BITCOIN](https://api.alternative.me/v2/ticker/Bitcoin/?convert=USD)

[ETHEREUM](https://api.alternative.me/v2/ticker/Ethereum/?convert=USD)


## CONTRIBUTORS

*Marcus LeGare (Author, Developer)*


## LICENSE

**COLUMBIA UNIVERISTY FINTECH BOOTCAMP**
