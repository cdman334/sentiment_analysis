# Sentimental Stock Analysis

## Table of Contents
1. [Description](#description)
2. [Installation and Setup](#installation-and-setup)
3. [Usage](#usage)
   - [Import Libraries](#import-libraries)
   - [Load Configuration](#load-configuration)
   - [Data Fetching and Analysis](#data-fetching-and-analysis)
   - [Visualization](#visualization)

## Description <a name="description"></a>
This project analyzes stock prices in correlation with news sentiments. It employs data fetching, sentiment analysis, and visualization to provide insights into how news sentiments might impact stock prices.

## Installation and Setup <a name="installation-and-setup"></a>

1. **Prerequisites**: 
   - Ensure you have Python installed.
   - Necessary libraries: yfinance, TextBlob, requests, pandas, matplotlib.

2. **Configuration**:
   - The project requires an API key to fetch news articles.
   - Store your API key in a `config.json` file within the project directory.

## Usage <a name="usage"></a>

### Import Libraries <a name="import-libraries"></a>
The project uses various libraries for data analysis, visualization, and sentiment analysis. Ensure you have these libraries installed or use `pip install` to get them.

### Load Configuration <a name="load-configuration"></a>
The API key for fetching news articles is read from a `config.json` file.

### Data Fetching and Analysis <a name="data-fetching-and-analysis"></a>
Several helper functions are defined to fetch stock data, retrieve news articles, and analyze sentiments.

### Visualization <a name="visualization"></a>
Use the visualization functions to plot and understand the correlation between stock prices and news sentiments.
