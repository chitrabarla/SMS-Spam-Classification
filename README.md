# SMS-Spam-Classification

SMS Spam collection dataset is from the UCI Machine Learning repository 

The dataset contains a set of SMS messages in English, tagged according being ham(legitimate) or spam(illegitimate). 
It contains one message data per line. Each line is composed by two columns: v1 contains the label (ham or spam) and 
v2 contains the raw text. There are 5,574 such entries.
    
The main feature that are utilized in our model is the text message i.e. the v2 column. Each row consists of a set of words. 
These set of raw words have to be analyzed to classify them as ham or spam. Therefore it mainly consists categorical data. 

Data preprocessing techniques are applied to extract the most relevant words from the set of raw words to use in 
the classification models. Input dataset was preprocessed, split to training, validation and testing sets using 
K-fold Cross Validation techniques. Count Vectorization method was applied to transform the text of the SMS messages. 

The ML models used for the classification task are Naive Bayes algorithm, Support Vector Machine, Logistic Regression, 
k-Nearest Neighbor and the Random Forest algorithms.


Classification Model                      Accuracy(Percent)
Multinomial NB                                99.28%
Random Forest                                 97.66%
Logistic Regression                           98.74%
SVM                                           98.74%
KNN                                           96.94%
Ada Boost                                     98.56%
Decision Tree                                 96.95%
Neural Network                                98.92%
 

To run the jupyter notebook file, please follow the instructions as below:

Pre-Requisites:
 1. Install Jupyter Notebook.
 2. The latest versions of the following libraries should be installed:
   pandas, numpy, scipy, matplotlib.pyplot, seaborn, sklearn, nltk, wordcloud
