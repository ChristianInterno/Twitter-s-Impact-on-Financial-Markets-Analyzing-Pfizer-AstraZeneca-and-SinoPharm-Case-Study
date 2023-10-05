# Analyzing the Impact of Twitter on Financial Markets: A Case Study of Pfizer, AstraZeneca, and Sinopharm

This project is a part of the Data Management coursework at the University of Milano Bicocca - Data Science. Our main goal was to understand the potential influence of tweets related to specific pharmaceutical companies on their respective stock market trends. 

## Objective

We concentrated our study on three major pharmaceutical companies that produced COVID-19 vaccines: 
- Sinopharm
- AstraZeneca
- Pfizer

Our approach involved extracting tweets that mentioned at least one of the aforementioned companies and subsequently integrating this data with stock market trends. Through visualizations, we were able to observe the daily and hourly patterns of tweet counts and stock market movements, factoring in sentiment analysis and tweet engagement. Despite our thorough analysis, the visuals did not conclusively establish a direct correlation between the tweet and stock trends.

## Tools Used

- **Data Integration**: Python Notebooks
- **Visualization**: Tableau

## Repository Structure

### `Data gathering` folder:

This folder contains Python notebooks used in the data collection phase:

1. **A-Snscraper**: For tweet collection
2. **B-Data stock**: For collecting stock market data
3. **A-Data merge stock**: To merge different stock datasets
4. **Integration_Sinopharm**: Combines Sinopharm tweets with stock data
5. **Integration_Astrazeneca**: Merges AstraZeneca tweets with stock data
6. **Integration_Pfizer**: Integrates Pfizer tweets with stock data

### `Real-time` folder:

Inside this folder:

- Kafka producer and consumer for financial data and tweets
- Nifi workflow representation
- Real-time data integration processes

### `Data` folder:

This folder houses:
- Action-related data
- Tweet datasets
- Integrated data sets
