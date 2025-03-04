# Tweet-Sentiment-Analysis
The Sentimental analysis is the digital methodology,  which is a Machine Learning techniques that uses a Python programme to analyse large amounts of scientific data. The method of measuring and identifying feelings associated with a particular event is called sentiment analysis, aiming to identify and classify the emotions represented in a sample by separating them into favourable, adverse and neutral attitudes. 

The gathered data were filtered and sanitised before sentiment analysis using the following standards:
  •	Retweets have been cleared off
  •	URLs were eliminated.
  •	The tweets that were chosen have to be at least 80 characters long (without the hashtag).
  •	The tweets were edited to remove any mention of the business
  •	Spaces were used in place of special characters like "", "=", or "!"

Two sets of tweets are created: training data and testing data. The dataset is then exposed to 3 interfaces: fit(), predict(), transform().
Models used:
  •	BernoulliNB - Bernoulli Naive Bayes
  •	LinearSVC - Linear Support Vector Classification
  •	LR - Logistic Regression
Confusion matrix is plotted for all of them. 
