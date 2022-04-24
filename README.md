# A financial planner for emergencies
A tool to help credit union members evaluate their financial health. Specifically,able to assess their monthly budgets,forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

## Technologies

- Jupyter notebook
- MonteCarlo Simulation
- Alpaca SDK
- Pandas library for data analysis, and visualizations.
---

## Usage:
- The members will be able to use this tool to visualize their current savings,and determine if they have enough reserves for an emergency fund.

- This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## 1.Financial Planner for Emergencies
Determine the current value of a member’s cryptocurrency wallet.  

- Used the Requests library to get the current price (in US dollars) of Bitcoin (BTC) and Ethereum (ETH) by using the API endpoints that the starter code supplied.
- Calculated the value, in US dollars, of the current amount of each cryptocurrency and of the entire cryptocurrency wallet


---

## 2. Evaluated the Stock and Bond Holdings by Using the Alpaca SDK
API call to Alpaca via the Alpaca SDK to get the current closing prices of the SPDR S&P 500 ETF Trust (ticker: SPY) and of the iShares Core US Aggregate Bond ETF (ticker: AGG).

- Get the current closing prices for SPY and AGG by using the Alpaca get_bars function. Formated the response as a Pandas DataFrame by including the df property at the end of the get_bars function.

- Calculated the value, in US dollars, of the current amount of shares in each of the stock and bond portions of the portfolio, and print the results.

---

## 3. Evaluate the Emergency Fund
To determine if the credit union member has enough savings to build an emergency fund into their financial plan.

---

## 4. Financial Planner for Retirement
Used the Alpaca API to get historical closing prices for a retirement portfolio. then running the Monte Carlo simulations to forecast the portfolio performance over 30 years. 

1. Plot the probability distribution of the Monte Carlo simulation.
2. Generate the summary statistics for the Monte Carlo simulation. 

---

## 5. Forecast Cumulative Returns in 10 Years
Adjust the retirement portfolio and run a new Monte Carlo simulation to find out if the changes will allow members to retire earlier.


--- 

##  Contributors
Brought to you by Carlos Polanco.

- Email: carlos.polanco0508@gmail.com
- GithubProfile: https://github.com/carlosmpr
- Linkedin: https://www.linkedin.com/in/carlosmpr/

---

## License

MIT

Copyright (c) 2012-2022

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.