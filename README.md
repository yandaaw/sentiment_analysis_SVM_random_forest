# <p align="center">
  <h1 align="center">Implementation Of Text Mining In The Analysis Of Indonesian Public Opinion Sentiment On Covid-19 Vaccination On Twitter Social Media Using Text Classification Support Vector Machine And Random Forest</h1>
</p>

# Abstract
The purpose of this study is to implement text mining for sentiment analysis of Indonesian public opinion on COVID-19 vaccination on Twitter social media using text classification techniques Support Vector Machine (SVM) and Random Forest. The research begins with crawling data from Twitter from September 2021 to October 2021; data cleansing; text translation into English; data preprocessing using NTLK performed with and without the lemmatization process; sentiment analysis using TextBlob; distribution of training and testing data with the Hold-Out method of 70:30 and 80:20; hyperparameter tuning with GridSearchCV; text classification with SVM and Random Forest; and testing the classification results by calculating Accuracy, Precision, Recall, F-Measure based on confusion matrix. The results show that text classification Random Forest consistently has a higher accuracy rate than SVM with the highest accuracy value of 90,59% and most of the sentiments indicate neutral to the COVID-19 vaccination program.

**Keyword**: ```sentiment analysis, text mining, Twitter, SVM, Random Forest```

<!-- TABLE OF CONTENTS -->
  <h2 style="display: inline-block">Table of Contents</h2>
  <ol>
    <li><a href="#abstract">Abstract</a>
    <li><a href="#about-the-project">About The Project</a>
    <li><a href="#built-with">Built with</a></li>
    <li><a href="#results-and-conclusions">Results and Conclusions</a></li>
  </ol>

# About The Project
![Poster 5 Minutes Thesis Presentation Odd Semester 20212022 - LZ11 - Group 13_A2_REV](https://user-images.githubusercontent.com/73176284/163113157-ec43290e-e194-490f-b7d5-765d30c5148b.jpg)

# Built with
The following are the data libraries used in building this project:
- [**pandas**](https://pandas.pydata.org/)<br>
- [**NumPy**](https://numpy.org/)<br>
- [**tweepy**](https://www.tweepy.org/)<br>
- [**textblob**](https://textblob.readthedocs.io/en/dev/)
- [**NLTK**](https://www.nltk.org/)
- [**scikit-learn**](https://scikit-learn.org/)
- [**seaborn**](https://seaborn.pydata.org/)<br>
- [**matplotlib**](https://matplotlib.org/)<br>
- [**plotly**](https://plotly.com/)<br>
- [**SciPy**](https://scipy.org/)

# Results and Conclusions
  This research aims to implement text mining in the analysis of Indonesian public opinion sentiment on the implementation of COVID-19 vaccination in Indonesia using text classification techniques Support Vector Machine and Random Forest and measure the accuracy of the two algorithms. In this study, the object of research uses data from Twitter in the form of Indonesian-language tweets. Tweets taken are tweets related to the implementation of the COVID-19 vaccination, and the keyword used in the crawling process is "vaccination". The data retrieval was carried out in the period from September 2021 to October 2021, totaling 2,500 tweets.
  The results showed that in the two algorithms used, namely Support Vector Machine and Random Forest, there was a significant difference in the level of accuracy. Random Forest has a higher accuracy value of 4.53% than the Support Vector Machine. From all the experiments, both the experiments conducted with the distribution of training-testing data at 70:30 and 80:20, and the data processing process with and without lemmatization, it was found that Random Forest consistently has a higher level of accuracy than the Support Vector Machine, with an accuracy rate of the highest of 90.59% obtained with data through the lemmatization process and the distribution of training-testing data of 70:30. Therefore, the two null hypotheses (H0) have been met, namely there is a difference in the level of accuracy between the two algorithms and the level of accuracy of Random Forest is higher than the Support Vector Machine. From the results of this study, it can also be concluded that the effect of selecting parameter values ​​in the hyperparameter tuning process affects the accuracy of the two algorithms.
  Based on this sentiment analysis research, it shows that neutral sentiment gets the highest value compared to other sentiments, with a percentage value of 67%. Followed by the percentage of positive sentiment of 24% and the percentage of negative sentiment of 9%. This shows that most Indonesians during this period tended to have a neutral opinion regarding the implementation of the COVID-19 vaccination organized by the government.
