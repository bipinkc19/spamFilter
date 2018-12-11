# Spam Filter of Emails 
Spam filter using Multinomial Naive Bayes classifier by count vectorization and TF-IDF.

## Algorithm
Naive Bayes is an excellent algorithm that uses the probability of different features that we consider here independent.
Although this is not the case in real life Bayes has proved to solve many complex problems with high accuracy.
Multinomial is an implementation of Naive Bayes specially designed for NLP.

## Findings:
- Count vectorization worked better than TF-IDF.
- Words that are most repetitive in spam and ham messages are a clear classifier.
- By TF-IDF we would be decreasing the importance of this.
- Also, it is caused by previously removing stop words.
- Different data set has different tools to be used like in our case the most common tf-idf was performing lower than count vectorization.
