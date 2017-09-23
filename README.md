# id-hatespeech-detection

<b>Detecting Hate Speech on Tweets in Indonesian Language Using Machine Learning Approach</b><br>

This research aims to detect hate speech  on tweets in Indonesian language. 
The objective of this research is to compare the performance of several features and machine learning algorithms for hate speech detection. Features that extracted in this research are word n-gram with n=1 and n=2, character n-gram with n=3 and n=4, and negative sentiment. 
Classification is performed using Naïve Bayes, Bayesian Logistic Regression, Random Forest Decision Tree, and Support Vector Machine. An 88,6% F-Measure average is achieved when using word n-gram feature with Bayesian Logistic Regression. Results also show that word n-gram feature outperforms character n-gram.

<b>Dataset</b><br>
The dataset is a two columns data of: tweet - label, consist of 705 tweets in Indonesian language.
The label is Non_HT or HT. Non_HT for "non hate speech" tweet and HT for "hate speech" tweet. 
Number of Non_HT tweets: 445
Number of HT tweets: 260

The dataset is available for personal use, but if you want to publish paper using the dataset you should cite this publication:

Ika Alfina, Rio Mulia, and Mohamad Ivan Fanany, <i>"A Dataset and A Preliminary Study For Hate Speech Detection in Indonesian Language 
"</i>, in Proceeding of International Conference on Advanced Computer Science and Information Systems (ICACSIS) 2017 in Bali, Indonesia (accepted).
