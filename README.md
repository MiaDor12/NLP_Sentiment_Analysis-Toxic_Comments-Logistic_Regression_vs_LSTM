# NLP Sentiment Analysis - Toxic Comments - Logistic Regression vs LSTM
* The notebooks contain NLP sentiment classifications of comments into several class labels of several types of verbal violence.
* The dataset is from kaggle: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge.
* The first notebook (NLP_Sentiment_Analysis-Toxic_Comments-with_sklearn.ipynb) provides a linear baseline for this contest using logistic regression.
* The predictions that I submitted to kaggle got an avg AUC score of 0.83514.
* In the second notebook (NLP_Sentiment_Analysis-Toxic_Comments-with_Keras.ipynb) I chose to use embedding and bidirectional LSTM (using Keras) as the prediction model.
* Using the deep learning model, the predictions that I submitted to kaggle got an avg AUC score of 0.97163.
* This means that the deep learning model increased the score by more than 13 percentage points!

For better viewing of the notebooks: 
* First notebook (logistic regression): https://nbviewer.jupyter.org/github/MiaDor12/NLP_Sentiment_Analysis-Toxic_Comments-Logistic_Regression_vs_LSTM/blob/master/NLP_Sentiment_Analysis-Toxic_Comments-with_sklearn.ipynb
* Second notebook (LSTM): https://nbviewer.jupyter.org/github/MiaDor12/NLP_Sentiment_Analysis-Toxic_Comments-Logistic_Regression_vs_LSTM/blob/master/NLP_Sentiment_Analysis-Toxic_Comments-with_Keras.ipynb
