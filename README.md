Monte Carlo Simulation for Stock Price Forecasting
This project implements a Monte Carlo simulation to forecast the future stock prices of Microsoft (MSFT) using historical data and advanced statistical methods, including GARCH models for volatility estimation. The project demonstrates the application of quantitative finance techniques to predict stock price movements and assess potential risks.

Project Overview
The goal of this project is to forecast the future stock prices of Microsoft by:

Downloading historical stock price data.
Calculating log returns.
Modeling volatility using GARCH.
Running a Monte Carlo simulation to generate future price trajectories.
Visualizing the simulation results and forecasting volatility.
Key Features
Data Collection: Historical stock prices are downloaded using the yfinance library.
Log Returns Calculation: Log returns are computed from the adjusted close prices.
GARCH Model: The GARCH(1,1) model is fitted to the log returns to estimate and forecast volatility.
Monte Carlo Simulation: Future price trajectories are simulated using the estimated drift and volatility.
Visualization: The results are visualized using matplotlib and plotly for interactive plots.
Project Structure
main.py: The main script that executes the entire workflow.
README.md: This file, providing an overview of the project.
requirements.txt: List of required Python packages.
Installation
To run this project, you'll need to have Python installed along with the following packages:

numpy
pandas
yfinance
matplotlib
plotly
arch
You can install the required packages using the following command:
