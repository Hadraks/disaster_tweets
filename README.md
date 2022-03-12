# disaster_tweets
Analyzing tweets about disasters

Twitter is an enormous source of real time, often geo tagged information about the world. This information can be incredibly useful in understanding the location, scale and nature of disasters. 

Business proposal
Analysis of tweets could be another method of obtaining information for government and disaster relief agencies. This information can be used to identify emerging disasters or to gain greater information about ongoing disasters. Tweets include pictures which can illustrate the scope and nature of disasters allowing for a more appropriate and effective response.
There are an enormous number of tweets so there has to be a method of identifying which tweets are related to disasters in general and to specific disasters. An algorithm like this can identify relevant tweets which are fed to a human to first determine relevance and then pass on the information to the appropriate agency.

Data
This data set includes 7500 tweets which include a disaster key word such as fire or earthquake. These were all scored by people as either a “disaster” or “not disaster”. Some are geo tagged and all include text.

Methods 
Standard natural language processing techniques such as remove stop words, word stemming, lowercasing, and tokenizing were applied. TF-IDF and Count Vectorizing were both applied as well as Word 2 Vec and TSNE, a form of principal component analysis. 

Results
The primary result is after NLP processing the various models used all were able to identify the disaster tweets roughly 80% of the time, as opposed to the dummy classifier which could identify disaster tweets 57% of the time. 
A second finding was regarding the relation of keywords to disasters. Certain keywords, like debris, wreckage, and derailment were found to be connected to disaster 100% of the time while other keywords, such as aftershock and body bags were found to have almost no relation to disasters.
Word 2 Vec analyzed similar words to keywords and keywords were analyzed using k means clustering to see the relation between the keywords. 

Conclusions
NLP and modeling was considerably more successful than the dummy model indicating that this is an effective way to identify tweets related to disaster.
Searching for keywords related to disasters may be effective and our findings indicate that certain keywords are very connected to disasters and other words that seem related to disasters are not. These results allow for more effective searching for tweets.
When there is an ongoing disaster, searching twitter for similar and relevant words (such jolted when an earthquake recently happened), especially in geotagged tweets could be an effective way to gain more information. 
