# TwitterSentimentAnalysisPythonBlob
This script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event 

![TwitterSentimentAnalysisPythonBlob](TwitterSentimentAnalysisPythonBlob.png)

# Getting Started

First of all login from your Twitter account and goto [Twitter Apps](https://apps.twitter.com/). Create a new app ([How to create twitter app](http://www.letscodepro.com/twitter-sentiment-analysis/)) and goto __Keys and access tokens__ and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later. 

# Installation
```
pip install tweepy
```
```
pip install matplotlib
```
```
pip install textblob
```

### Usage

Once you have created an app on twitter and installed all the dependencies
 open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret.
 After that save and run the script. You will be prompted to enter the keyword/hashtag
 you want to analyze and the number of tweets you want to analyze.
 Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.

## Built With

* Python 3.6
* tweepy
* textblob
* matplotlib

