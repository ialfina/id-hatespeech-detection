# id-hatespeech-detection

<b>A Dataset and A Preliminary Study For Hate Speech Detection in Indonesian Language</b><br>

The objective of our work is to detect hate speech in Indonesian language. But so far research on this subject is still very rare. The only research we found has created a dataset for hate speech against religion, but the quality of this dataset is inadequate. Our research aimed to create a new dataset that covers hate speech in general, including hatred for religion, race, ethnicity and gender. In addition, we also conducted a preliminary study using machine learning approach. Machine learning so far is the most frequently used approach in classifying text. We compared the performance of several features and machine learning algorithms for hate speech detection. Features that extracted in this research are word n-gram with n=1 and n=2, character n-gram with n=3 and n=4, and negative sentiment. Classification was performed using Naïve Bayes, Bayesian Logistic Regression, Random Forest Decision Tree, and Support Vector Machine. An 88,6% F-Measure is achieved when using word n-gram feature with Bayesian Logistic Regression. Results also show that word n-gram feature outperforms character n-gram.
<br>
<b>Dataset</b><br>
The dataset is a two columns data of: label - tweet, consist of 713 tweets in Indonesian language.
The label is Non_HS or HS. Non_HS for "non hate speech" tweet and HS for "hate speech" tweet. 
Number of Non_HT tweets: 453
Number of HT tweets: 260
Since this dataset is unbalance, you might have to over-sampling/down-sampling in order to create a balanced dataset.

The dataset is available for personal use, but if you want to publish paper using the dataset, please cite this publication:

Ika Alfina, Rio Mulia, and Mohamad Ivan Fanany, <i>"A Dataset and A Preliminary Study For Hate Speech Detection in Indonesian Language 
"</i>, in Proceeding of International Conference on Advanced Computer Science and Information Systems (ICACSIS) 2017 in Bali, Indonesia (accepted).
