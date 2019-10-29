![alt text](https://github.com/raffisahakyan/Company_Sentiment_Analysis_via_Twitter/blob/master/WordCloud.png)

# Company Name Sentiment Analysis via Twitter API

Twitter is a huge dataset of customer insights that businesses desperately need to acquire insights from. According to Internet Live Stats, there 8868 tweets posted on Twitter per second. Currently, Twitter provides developer accounts with 15mins delayed access to tweets. This API is used in this project to retrieve tweets that mention the company brand name. Once we gather the tweets we will apply data preprocessing to clean the data up, then apply sentiment analysis for polarity check. The next step will include the visualization of the results in a bar plot and generation of WordCloud with the most frequent words. The final step of the project includes the illustration of the tweets on the world map.  
## Getting Started

For this project you will need to apply for the Twitter Developer Account [here](https://developer.twitter.com/en/apply-for-access.html). The Twitter team usually approves the educational purpose accounts within one day.

Additionally, you will need an access to OpenMapQuest Geocoding API for world mapping [here](https://developer.mapquest.com). OpenMapQuest provides free access to its API for 15,000 transactions. Notably, it has certain requirements on referencing their product.  

### Prerequisites

Besides general use libraries you will also need to import [tweepy](https://www.tweepy.org), [tweet-preprocessor](https://pypi.org/project/tweet-preprocessor/) , [folium](https://github.com/python-visualization/folium) and [geopy](https://github.com/geopy/geopy).  

## Authors

* **Raffi Sahakyan** MS in Business Aanlytics Candidate 2020 at UCLA Anderson - [LinkedIn](https://linkedin.com/in/raffi-sahakyan)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspiration of this project was a 5 day Python Bootcamp taught by Paul Deitel at UCLA Anderson School of Management, as part of the MSBA Class of 2020 Orientation program. 

## Extra Links
* [A Friend's link](https://medium.com/@raffisahakyan/sentiment-analysis-on-tweets-d12b04072e08?source=friends_link&sk=e14c5f5a1d5aecdf56cdfae34243eeca) for my Medium article on this topic.
