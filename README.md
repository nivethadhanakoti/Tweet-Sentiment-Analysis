# Tweet-Sentiment-Analysis
The Sentimental analysis is the digital methodology,  which is a Machine Learning techniques that uses a Python programme to analyse large amounts of scientific data. The method of measuring and identifying feelings associated with a particular event is called sentiment analysis, aiming to identify and classify the emotions represented in a sample by separating them into favourable, adverse and neutral attitudes. <br>

The gathered data were filtered and sanitised before sentiment analysis using the following standards:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	Retweets have been cleared off<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	URLs were eliminate<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	The tweets that were chosen have to be at least 80 characters long (without the hashtag).<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	The tweets were edited to remove any mention of the business<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	Spaces were used in place of special characters like "", "=", or "!"<br>

Two sets of tweets are created: training data and testing data. The dataset is then exposed to 3 interfaces: fit(), predict(), transform().<br>
Models used:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	BernoulliNB - Bernoulli Naive Bayes<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	LinearSVC - Linear Support Vector Classification<br>
  &nbsp;&nbsp;&nbsp;&nbsp;•	LR - Logistic Regression<br>
Confusion matrix is plotted for all of them. 
