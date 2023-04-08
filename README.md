# AI-Project

This is the repository to our final Intro to AI project:
Parsing tweets about the train derailment in East Palestine, Ohio, to ...

Team Members:   
Elaine Zhang (yizhang5), Mahrukh Khan (mahrukhk), Ricardo Ibarra-Gil (ribarrag)  


Tweets were fetched with two different queries:
**1. Tweets containing the terms East Palestine AND (tran derailment OR Norfolk), from February 1 to March 15: 447k tweets**

The file DatasetOne.csv contains all these data (1.05 Gb)

**2. Tweets containing the terms tran AND Norfolk, from February 13 to March 15, 2023: 124k tweets**

The file NorfolkTrain.jsonl contains all this data as a JSONLine file. 
I was told it includes some 124k tweets, replies to tweets and some other useful information about the tweets, but haven't parsed it to confirm.

The file Tweet.csv contains those same tweets in a csv file, and then the files URL.csv, Hashtag.csv, and Agent.csv have information about those same tweets and their authors, and are connected using the variable NodeID.

I am not sure if there is some data loss from the JSONL file and the csv files. I think there may be but not sure. I was told the JSONL contains replies to tweets, which the csv doesn't, but hasnt corroborated that.

Perhaps we can spend a bit of time trying to parse JSONL file, and if not successful, then just go directly with csv files.

## About the files:

Data_parsing notebook is claeaning datasets 2 and 3, standa

There are TWO data foldres:
raw_data <- git ignored because contains the raw data sets, some of them > 1 Gb, not supported by Github
data <- contains final data set that we should use

raw_data is called by Data_parsing notebook


