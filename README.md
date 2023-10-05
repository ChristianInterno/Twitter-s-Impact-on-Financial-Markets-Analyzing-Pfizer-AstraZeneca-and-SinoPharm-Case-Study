# Twitter's Impact on Financial Markets: Analyzing Pfizer, AstraZeneca, and SinoPharm Case Study

![Header Image]([https://images.unsplash.com/photo-1563013544-824ae1b704d3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80](https://www.europeanpharmaceuticalreview.com/wp-content/uploads/COVID-19-vaccine-finance-MCAP.jpg)

> **A Data Management Project at the University of Milano Bicocca - Data Science.** 

This project delves into understanding the potential influence of tweets on stock market trends. We've focused our study on three prominent pharmaceutical companies that played pivotal roles during the COVID-19 pandemic by producing vaccines: **Sinopharm**, **AstraZeneca**, and **Pfizer**. By integrating tweet data with stock market trends, we aim to uncover any correlations and insights into the interplay of social media sentiment and stock market fluctuations.

## 📈 Project Highlights

1. **Tweet Extraction**: Gathered tweets containing mentions of the three pharmaceutical companies.
2. **Stock Data Integration**: Combined tweet data with stock market data to observe potential correlations.
3. **Visualization**: Utilized Tableau to graphically represent daily and hourly trends, incorporating sentiment analysis and tweet engagement metrics.
4. **Real-time Data Workflow**: Leveraged Kafka and Nifi for real-time financial data and tweet integrations.

## 📁 Repository Structure

- **Data gathering**: Contains Python notebooks for data collection.
  - `A-Snscraper`: For collecting tweets.
  - `B-Data stock`: For gathering stock data.
  - `A-Data merge stock`: Merges stock datasets.
  - `Integration_Sinopharm`: Integrates Sinopharm tweets and stock data.
  - `Integration_Astrazeneca`: Integrates Astrazeneca tweets and stock data.
  - `Integration_Pfizer`: Integrates Pfizer tweets and stock data.
  
- **Real-time**: Features Kafka producers and consumers for financial data and tweets.
  - Real-time integrations are present in the integration folder.
  
- **Data**: Houses data related to tweets, stock actions, and integrated datasets.

## 🛠 Tools & Technologies

- **Data Collection**: Python (Notebooks)
- **Visualization**: Tableau
- **Real-time Data Processing**: Kafka, Nifi

## 🤔 Findings

While our visualizations beautifully represent the intertwined nature of tweets and stock market trends, a definitive correlation between the two could not be conclusively determined. However, the methodologies and the workflow established can serve as a foundation for more extensive future studies.

## 📫 Contact

For any queries or further discussions related to this project, feel free to connect with the main contributor: [Christian Internò](https://github.com/ChristianInterno).

---

**Disclaimer**: This project is for academic and research purposes only. Any insights or findings should not be used for financial or investment decisions.

