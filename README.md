# AI-Project

This is the repository to our final Intro to AI project:
Parsing tweets about the train derailment in East Palestine, Ohio, to ...

Team Members:   
Elaine Zhang (yizhang5), Mahrukh Khan (mahrukhk), Ricardo Ibarra-Gil (ribarrag)  

## Data sources

Tweets were fetched with two different queries:
**1. Tweets containing the terms East Palestine AND (tran derailment OR Norfolk), from February 1 to March 15: 447k tweets**

The file DatasetOne.csv contains all these data (1.05 Gb)
The file DatasetTwo.csv contains another (smaller) subset of this same query (700 Mb)

There are many duplicates between these tow data sets

**2. Tweets containing the terms tran AND Norfolk, from February 13 to March 15, 2023: 124k tweets**

The file Tweet.csv contains those same tweets in a csv file, and then the files URL.csv, Hashtag.csv, and Agent.csv have information about those same tweets and their authors.

## About the files:

Data_parsing notebook is claeaning datasets DatasetOne and DatasetTwo, and merging the data set Tweet.csv already cleaned.
It also outputs the final dataset (data_tweets.csv) into the data/ folder.

There are TWO data folders:
raw_data <- git ignored because contains the raw data sets, some of them > 1 Gb, not supported by Github
data <- contains final data set that we should use
(raw_data is called by Data_parsing notebook)


