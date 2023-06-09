Train Derailment in Eastern Ohio  
95891 – Introduction to Artificial Intelligence  
Course Project Proposal  
Team Members:   
Elaine Zhang (yizhang5), Mahrukh Khan (mahrukhk), Ricardo Ibarra-Gil (ribarrag)  
<br>
<b>Project Description  </b><br>
<br>
On February 3, 2023, a freight train carrying hazardous materials was derailed in Eastern Ohio. The initial reaction by the government and the public was mixed and there was a sense of confusion regarding the scale of the disaster. 

We hypothesize that initial reports coming in from government channels were not clear on the extent of the disaster. On the other hand, the locals living in the area and in nearby towns - as far as in Pennsylvania, were worried about water and air contamination. It was only after a few days that the media picked up the news and the government switched to a more aggressive approach towards tackling the situation. 

We intend to confirm this hypothesis by analyzing tweets from government-run twitter accounts, news channels, and the public.

<b>Input Data Source</b><br>
Scraped data from tweets between February 3 - March 15, 2023
News articles 
 
<b>Model Usage & Reference </b><br>
Topic modeling leveraging Latent Dirichlet Allocation
Unsupervised sentiment analysis using a lexicon-based approach (such as NLTK’s Vader)

The first method will provide the underlying topics in the tweets, while the output from the second will inform about the sentiment of the tweets. The combined result will provide insights into how sentiment may be related to particular topics or topics of discussion in the context of the train derailment in East Palestine. This will also help us understand if the general nature of tweets right before and after the incident were different for different twitter accounts i.e. government, public, media.
<br>


<b>Main Challenges</b><br>
Data acquisition:
Acquire enough train derailment-related social media data to perform analysis
Determine relevant twitter accounts for media and government
Data analysis:
Working with non labeled data to perform sentiment analysis
Sharing our findings:
We will need to adapt our communication strategy to the results we get from the analysis
<br>

<b>Evaluation Metrics for Success</b><br>
Since we work on an unsupervised learning problem, we may have a narrower variety of defined quantitative metrics for those supervised problems like accuracy or F1-score. Therefore, we will use some quantitative metrics to evaluate our results, but we will also evaluate our results from two additional aspects.
On the one hand, for topic modeling we will use metrics such as:
Coherence scores, which measures semantic similarity of the words in a single topic
Perplexity, which measures the prediction capacity of the model.
On the other hand, for the overall project, we will pay attention to two aspects:
Outcome-oriented evaluation: When we perform grid search for some hyperparameters of models, we will check the generated results and select the most reasonable one which can verify our hypothesis.
Knowledge-based evaluation: When we get insights from the results generated by models, we will check whether they are consistent with knowledge from real worlds (e.g. news, reports).


