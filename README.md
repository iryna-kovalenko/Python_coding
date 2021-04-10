# Python_coding
Twitter sentiment analysis of covid-19 relates tweets.
Data extraction - downloaded tweets ID's and used hydrator to extract the tweets from Twitter.

Pre-processing - removed hashtags, URL,@usernames, punctuation, stop-words, numbers, converted all words to a lower case.
Removed duplicate tweets, stemmed tweets and lexicon

Annotation - annotated tweets. 

Generating models - 1) random data split, 2) stratified k-fold 
Models used: 1) Logistic Regression 2)K Nearest Neighbors 3)Multinomial naïve Bayes 4)Complement Naive Bayes 5) Gaussian naïve Bayes
