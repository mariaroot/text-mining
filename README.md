# READ ME

## Text mining task

Text classification and sentiment analysis are often conducted on a paragraph of text or more (e.g. a whole review or a book chapter). In this task I build simple models to perform text classification and sentiment analysis on individual sentences from Amazon reviews.

For this task, I used the ‘Sentiment Labelled Sentences’ dataset from UCI Irvine Machine Learning Repository (Kotzias, 2015; Kotzias et al., 2015). It consists of sentences from different review sites which have been labelled as positive (1) or negative (0). I used the subset of sentences from Amazon, which contained 500 sentences labelled positive and 500 labelled negative. The labelling of this dataset was done using a convolutional neural network. I will use these labels to train a simpler, Bag-of-Words model to perform classification, then check the performance of my model against the provided labels. I will then perform sentiment analysis on the text.