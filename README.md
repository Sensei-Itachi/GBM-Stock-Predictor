# GBM-Stock-Predictor
Monte Carlo Simulation to predict future stock prices
Geometric Brownian Motion Stock Price Simulation
Overview

This project explores the use of Geometric Brownian Motion (GBM) to model and simulate future stock price movements.

I developed this project to better understand how mathematical models are used in quantitative finance and portfolio analysis. Using historical stock data, the model estimates expected return and volatility, then generates simulated future price paths based on the assumptions of GBM.

The goal of this project is not to predict stock prices with certainty, but rather to explore how stochastic processes can be used to model uncertainty in financial markets.

Mathematical Background

Geometric Brownian Motion is a commonly used model in financial mathematics and is the foundation of asset pricing .

The model assumes that stock prices follow the stochastic differential equation:

dS = μSdt + σSdW

where:

S = stock price
μ = expected return (drift)
σ = volatility
dW = Brownian motion term


Features
Historical stock data analysis
Estimation of drift and volatility parameters
Monte Carlo simulation of future stock prices
Visualization of simulated price paths
Backtesting against historical market data

Motivation:

I became interested in quantitative finance after learning how mathematics, probability, and statistics are used to model financial markets.

This project allowed me to explore:

Stochastic processes
Probability theory
Financial modeling
Data analysis in Python

while gaining hands-on experience implementing mathematical concepts through code.

Results

Using historical market data, the model generates multiple simulated future price paths and compares them to actual market behavior.

Through backtesting, I observed that:

GBM can capture general market trends over long periods.
Simulated outcomes are highly sensitive to volatility estimates.
Real-world markets often violate several GBM assumptions, particularly during periods of extreme volatility.
Limitations

This model makes several simplifying assumptions(so do your own research):

Constant volatility
Constant expected return
Normally distributed log returns
No major market shocks

Technologies Used
Python
NumPy
Pandas
Matplotlib
Yahoo Finance Data (or other historical data sources)
