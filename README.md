# Final project repo for INFO 523 - Fall 2023.
## Tech Or Treat: The Sentimental Stock Saga

### Overview
This project conducts sentiment analysis on Apple stock using the `SentimentIntensityAnalyzer` from the `VaderSentiment` library in Python. The sentiment scores are compared with Apple stock prices, providing insights into the potential correlation between public sentiment and market dynamics.

#### Authors: Team Feature Finders Club - Eshaan Mathakari, Sanjay Bhargav Siddi, Likith Kumar Dundigalla,Aravind shrenivas Murali, Vamsi Vadala
#### Affiliation: School of Information, University of Arizona  

### Features
- Sentiment Analysis: Utilizes vaderSentiment's `SentimentIntensityAnalyzer` for sentiment analysis on textual data related to Apple stock.

- Data Retrieval: Fetches comprehensive stock data through API calls using the yfinance library.

- Data Visualization: Plots a comparison graph of Apple stock prices and sentiment scores to visually explore the relationship between sentiment and market trends.

### Requirements
- Python v3+
- Necessary Python libraries: vaderSentiment, yfinance, matplotlib


### Configuration
- Ensure that you have valid API keys for any external services used in fetching stock data.

- Adjust parameters such as the time frame for sentiment analysis and stock data retrieval in the script as needed.

### Results
The output folder contains the generated comparison plot, shedding light on the relationship between sentiment scores and Apple stock prices.

### Contributing
Feel free to contribute by opening issues, providing suggestions, or submitting pull requests.

#### Disclosure:
Derived from the original data viz course by Mine Çetinkaya-Rundel @ Duke University
