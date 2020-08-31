# Fighting Hate Using ML


# Aim
Sentiment Analysis of Tweets in Hinglish language and classify them as **normal**, **abusive** or **hateful** by applying *Naive Bayes Classifier*.


# Approach
Data set has been Collected from twitter using **tweepy** twitter api. The collected datasets has been manually labelled and then we performed following things:

## Steps
*1.* **Pre-processing of Datasets**: The tweets were first processed and the unnecessary information were deleted from the tweets like @ and symbols and others characters of length 3. Hash Tag were converted into normal words. Link were removed from tweets

*2.* **Tokenized**: The tweets were tokenized to split them word by word.

*3.* **Model Building**: From the processed tweets we created a Machine Learning Model for Naive Bayes Classifier. We split the data datasets into training and Testing Sets.(75-25 %)

*4.* **Prediction And Result**: We then test our model and perform the prediction on the testing sets and calculated the results. We got an accuracy of *76.35327635327636.*


![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)
![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg) 
![ForTheBadge built-by-developers](http://ForTheBadge.com/images/badges/built-by-developers.svg)
