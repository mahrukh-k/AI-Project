# AI-Project

This is the repository to our final Intro to AI project:
Parsing tweets about the train derailment in East Palestine, Ohio, to test our hypothesis that initial reports coming in from government channels were not clear on the extent of the disaster. On the other hand, the locals living in the area and in nearby towns - as far as in Pennsylvania, were worried about water and air contamination. It was only after a few days that the media picked up the news and the government switched to a more aggressive approach towards tackling the situation. 

Team Members:   
Elaine Zhang (yizhang5), Mahrukh Khan (mahrukhk), Ricardo Ibarra-Gil (ribarrag)  

## Data sources

Tweets were fetched with two different queries:
**1. Tweets containing the terms East Palestine AND (train derailment OR Norfolk), from February 1 to March 15: 447k tweets**

The file DatasetOne.csv contains all these data (1.05 Gb)
The file DatasetTwo.csv contains another (smaller) subset of this same query (700 Mb)

There are many duplicates between these two data sets

**2. Tweets containing the terms train AND Norfolk, from February 13 to March 15, 2023: 124k tweets**

The file Tweet.csv contains those same tweets in a csv file, and then the files URL.csv, Hashtag.csv, and Agent.csv have information about those same tweets and their authors.

## About the files:

Data_parsing_1 and Data_parsing_2 are cleaning datasets DatasetOne and DatasetTwo, and createing clean data version of the dataset
EDA is a rought exploratory descriptive analytics report, just to get a sense of the cleaned data
It also outputs the final dataset (data_tweets.csv) into the data/ folder.
LDA_analysis contains the code performing the topic modeling analysis
Preprocessing and Sentiment Analysis includes the bulk of the preprocessing and the Sentiment Analysis code

There are two data folders:
raw_data (hidden) <- git ignored because contains the raw data sets, some of them > 1 Gb
data <- contains final data set


