# Twitter Sentiment Analysis
## Objective
With the rampant that exist in this world, social media is "must" thing that is owned by all people to get information in this era. One of the most widely used social media platforms is Twitter. Twitter is a social media platform in micro-blogging form that was first launched in July 2006. With its presence, Twitter can influence the decisions that will be made by an investors when they want to invest in the company's shares. One of the business fields that can be used as a place to invest is a bank. In this research, an analysis was carried out to see the correlation between the Twitter sentiment with the movement of Bank Nasional Indonesia (BNI) stock data. All Twitter ata as a result of web scraping will be classified into positive or negative sentiments using Support Vector Machine (SVM) classification model. The result of sentiment classification and the movement of BNI stock price data will be analyzed using the pearson correlation test method and using linear regression algorithm-based modeling to find the effect of Twitter sentiment analysis with BNI stock price. 

## Data
This project uses 2 data sources, including:
1. Twitter Data
Twitter data utilized in this study is derived from web scraping with the keyword "BNI" using Twitter API and Tweepy Library. Web scraping process results 6 variable columns and 1000 rows of data. Among these 6 variables, only 2 will be utilized in this project, namely "Time" that is representing the timestamp of tweet uploads, and "Tweet" that is signifying the content of the uploaded tweets by users.
2. BNI Stock Price Data
The stock data for BNI serves as secondary data encompassing information pertaining to "Open", "Close", "High", "Low", "Adj Close", and "Volume". This dataset comprises 247 rows of data, with the relevant variables for this analysis being "Date" and "Close".

## Results
