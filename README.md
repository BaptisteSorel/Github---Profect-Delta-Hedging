# Delta Hedging Simulation for a multi-asset portfolio

## Project Summary
This project implements a Monte Carlo simulation to model and hedge a portfolio containing options on Microsoft (MSFT) and Apple (AAPL) stocks. It calculates the Profit and Loss (P&L) with and without delta-neutral hedging, using historical data and stochastic price paths, while incorporating implied volatility estimation and rebalancing frequency analysis.

## Description
**Purpose**: The goal is to demonstrate delta-neutral hedging techniques, simulate correlated stock price movements, and evaluate the effectiveness of the hedging strategy over one year. The project is structured in three main parts to explore different aspects of option pricing and hedging.

## Content
- [Delta_Hedging_MSFT_AAPL.ipynb](https://github.com/BaptisteSorel/Github---Profect-Delta-Hedging/blob/main/Python%20Project.ipynb): The main Jupyter Notebook containing the code, explanations, and results.
It is divided into three key parts :
. **Part 1 : implied volatility calculation**
  This section calculates implied volatility using the Black-Scholes model inverted with Newton-Raphson, applied to MSFT and AAPL option chains. It includes interpolation techniques  to estimate IV across different maturities, enhancing the accuracy of volatility inputs for simulations.
. **Part 2 : Basic Delta Hedging Simulation**
  Comparaison of a delta-hedged porfolio, balanced on a daily basis, versus an unhedged-one.
. **Part 3 : Influence of Delta Hedge Rebalancing Frequency**
  This part analyzes the impact of rebalancing frequency (daily, 2-day, weekly, monthly) on the hedged portfolio's P&L. It uses Monte Carlo simulations to compare performance across frequencies.
  

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/BaptisteSorel/Github---Project-Delta-HedgingL.git
 
