## Financial Planning with APIs and Simulations

we created two financial analysis tools by using a single Jupyter notebook:

- Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

- Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


## Technology:

to successfully use this file we need to download and set up the folowing programmes:

1-**python**
2- **pandas**`pip install pandas`
3- **jupyter lab** `pip install jupyter`
4- **Matplotlib** `install matplotlib`

## Important

* Make sure to add `.env` file with your Alpaca keys 
* Make sure you have the required libraries and dependancies:

- `import os`
- `import requests`
- `import json`
- `import pandas as pd`
- `from dotenv import load_dotenv`
- `import alpaca_trade_api as tradeapi`
- `from MCForecastTools import MCSimulation`
- `%matplotlib inline`



## Usage
The following image shows the histogram plot resulting from a simulation with these characteristics. However, because a random number generator is used to run each live Monte Carlo simulation, your image will differ slightly from this exact image:

![graph](https://github.com/karim985/Fintechallenge5/blob/main/Images/5-4-monte-carlo-histogram.png)

Run a Monte Carlo simulation of 500 samples and 30 years for the 60/40 portfolio, and then plot the results.The following image shows the overlay line plot resulting from a simulation with these characteristics. However, because a random number generator is used to run each live Monte Carlo simulation, your image will differ slightly from this exact image:

![graph](https://github.com/karim985/Fintechallenge5/blob/main/Images/5-4-monte-carlo-line-plot.png)

### Contributer 

Karim Bouzina [Linkedin](https://www.linkedin.com/feed/)

## Licence
Fintech UW edX Boot Camps
