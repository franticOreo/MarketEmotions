# MarketEmotions
Attempt at correlating stock market trends with emotions

#### Motivation
After reading the paper, Stock Prediction Using Twitter Sentiment Analysis by Mittal and Goel. I was interested in trying to implement some of the ideas with Python. 

#### Developments
The first barrier was attempting to receate their unique implementation of Profile of Mind State(POMS), a method of classifying words (in this case, tweets) to various mood dimensions. The paper did not offer exact descriptions of the assessment of the mood dimensions. I used NLTK's wordnet to generate Synsets to expand the traditional POMS words with synonyms. 
