# Challenge5_FinancialPlanning
![istockphoto-1166136976-612x612](https://user-images.githubusercontent.com/101449950/163918164-07cdbf72-1d52-4216-85bd-007ef3ba2575.jpeg)

## Background
My client in this exercise is a credit union. I need to build a tool to help the credit union members evaluate their financial health. That's very vague, however the credit union board wants its members to be able to assess their monthly budgets. They should also be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

### Project Outline
Part 1: Create a Financial Planner for Emergencies
  1. Evaluate the Cryptocurrency Wallet by Using the Requests Library
  2. Evaluate the Stock and Bond Holdings by Using the Alpaca SDK
  3. Evaluate the Emergency Fund

Part 2: Create a Planner for Retirement
  1. Create the Monte Carlo Simulation
  2. Analyze the Retirement Portfolio Forecasts
  3. Forecast Cumulative Returns in 10 Years

## Requirements/ Installations
The requirement.txt file in this repository contain all the packages you'll need in your conding env. Please make sure to install if you do not have them already. While you could use the package manager [pip](https://pip.pypa.io/en/stable/) to install these individually please make use of the requirement text in the repo.

### pip install for Requirements
```bash
python -m pip install -r requirements.txt
```
### Imports
```python
import numpy as np
import pandas as pd
import os
import alpaca_trade_api as tradeapi
import datetime as dt
import pytz
```

# A word about predictions 
![9780812973815](https://user-images.githubusercontent.com/101449950/163919796-3c537be4-c4c0-46cc-81f3-9031d3faa786.jpeg)

> “Consider a turkey that is fed every day. Every single feeding will firm up the bird’s belief that it is the general rule of life to be fed every day by friendly members of the human race “looking out for its best interests,” as a politician would say. On the afternoon of the Wednesday before Thanksgiving, something unexpected will happen to the turkey. It will incur a revision of belief.*” 
― Nassim Nicholas Taleb, The Black Swan: The Impact of the Highly Improbable

It important whenever we are talking about prediction in any discipline, finance of course included, to acknowledge our blind spots and the extent to which the  past can be a proxy for future occurrences. In thos exercise we used the Monte Carlo Method of simulation in order to predict future occurences in order to help credit union members plan for the future. 

# Code

# Resources
