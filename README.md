# Sentiment_Analysis_SVM
![](Results/SVM.png)
<br /> This Repository consist of project which we carried out as a part of my coursework in Machine Learning.
We implemented a Support Vector Classifier from scratch using (crammer-singer formulation, paper provided in the report folder) and trained it on the use case of sentiment analysis.
We did Sentiment Analysis on IMDB movie review data(from kaggle, whose link is provided in the data folder).
We are using famous IMDB’s movie review data set which contains 50,000 reviews in total
out of which 25,000 are positive and 25,000 are negative. Selection of the suitable pre-processing
methods come out to be a great step in improving the classification accuracy. Stop Words
removal, remove URLS, @, # and other special symbols, remove numbers, Stemming are the
pre-processing steps that we applied on our data. Furthermore, we emphasized on syntactical
features because our main focus was on the content of reviews.
We followed the n-gram model [1] for feature extraction & we worked with unigram, bigram,
trigram and combination of unigram, bigram & trigram with two different weighting schemes
viz. term frequency-inverse document frequency (tf-idf) and binary(bag of words). The ready
to fed data then fed to a Support Vector Classifier which is constructed from scratch and training of support vector machine classifier is done with the help of using labelled data. After this
classifier model is build which is able to classify the test data. Performance of this classifier for different n-grams has been compared with the sklearn inbuilt SVC model also.
