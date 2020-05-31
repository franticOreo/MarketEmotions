# MarketEmotions
Attempt at correlating stock market trends with emotions

#### Motivation
After reading the paper, Stock Prediction Using Twitter Sentiment Analysis by Mittal and Goel. I was interested in trying to implement some of the ideas with Python. 

#### Goal
Correlate twitter emotions with the Dow Jones Index during the June 2009

#### Developments
The first barrier was attempting to receate their unique implementation of Profile of Mind State(POMS), a method of classifying sentances (in this case, tweets) to various mood dimensions. The paper did not offer exact descriptions of the assessment of the mood dimensions. I used NLTK's wordnet to generate Synsets to expand the traditional POMS words with synonyms. The tweets were then scored for the moods that it exhibited. The scores were then grouped by date and plotted against the DJI index. 

![POMSoutput](https://imgur.com/eeQobSA)

Although, there appeared to be some trends between my scores and the DJI, they were quite different to the papers results. I am 
