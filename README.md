# Predicting stock performance with Long Short-Term Memory (LSTM)

## Overview

This project leverages Long Short-Term Memory (LSTM) networks to predict performance of various stocks, sector indices and market indices. The analysis uses stock prices for IBM, Apple, American Express, JPMorgan Chase, Exxon Mobil and Occidental Petroleum. Sector Indices include Financial Sector Index, Technology Sector Index and Energy Sector Index. Market indices include GDP, SP500 and Unemployment Data. 

The project covers Data Collection and Preprocessing, Explanatory Data Analysis (EDA), Univariate-, Bivariate-, and Multivariate Time Series Analysis, Time Series Decomposition, Stationary and Autocorrelation Tests, Feature Engineering, and the training of LSTM models to forecast variable prices.

## Table of Contents

1. Project Description
2. Data Sources
3. Variables
4. Features
5. Setup
6. Usage
7. Results
8. Contributing
9. License

## Project Description

This repository contains an R project that predicts stock performance using LSTM models. The project is documented in a Jupyter Notebook, covering steps from data collection and preprocessing to exploratory data analysis (EDA) and LSTM model training.

Goal of the project was to analyze stock market performance using time series analysis and build predictive models using LSTM modeling to forecast stock prices.

## Data Sources

### Stocks
IBM, Apple, American Express, JPMorgan Chase, Exxon Mobil, and Occidental Petroleum Data from Yahoo Finance.

### Sector Indices
Financial Sector Index, Technology Sector Index, and Energy Sector Index Data  from Yahoo Finance.

### Market Indices
GDP and Unemployment Data from the Federal Reserve Economic Data (FRED) database. SP500 from Yahoo Finance.

## Variables

Multiple variables in code are presented as their ticker symbol.

$IBM IBM                                     

$AAPL Apple                                    

$AXP American Express                         

$JPM JPMorgan Chase                           

$XOM Exxon Mobil                              

$OXY Occidental Petroleum   


$XLF Financial Sector Index

$XLK Technology Sector Index

$XLE Energy Sector Index


$GSPC SP500

$GDP GDP

$UNRATE Unemployment Rate


All stocks, sectors and SP500 have six columns; Open, High, Low, Close, Volume and Adjusted.

Open: The price at which the stock first traded upon the opening of the exchange on a given day.

High: The highest price at which the stock traded during the day.

Low: The lowest price at which the stock traded during the day.

Close: The price at which the stock last traded upon the close of the exchange on a given day.

Volume: The total number of shares traded during the day.

Adjusted: The closing price adjusted for dividends, stock splits, and other corporate actions to provide a more accurate reflection of the stock's value over time.











