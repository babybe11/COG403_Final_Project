# COG403 Final Project
## Sentiments from a Twitter Storm 

By Robin Medd and Shengye (Tony) Niu


The main file is 'codes.ipynd' where everything has been compiled. 

'cleaned_test_data.csv' has all the tweets that we retrieved from twitter for testing.

'feat_eng_train_data.csv' has 3% of the feature vectors of tweets from the VADER sentiment database.

'test_prediction_nb.npy' is a numpy arrary that contains the prediction results from testing our Naive Bayes Classifier

'test_prediction_svm.npy' is a numpy arrary that contains the prediction results from testing our SVM Classifier

'twitter_sentiment_naivebayes.pkl' is our Naive Bayes Classifier saved as a model trained on the VADER sentiment database.

'twitter_sentiment_svm.pkl' is our SVM Classifier saved as a model trained on the VADER sentiment database.

'y_predsNB.npy' is a numpy arrary that has the sentiment predictions of the testing part of our training data for our Naive Bayes Classifier. Used for the model evaluations.

'y_predsSVM.npy' is a numpy arrary that has the sentiment predictions of the testing part of our training data for our SVM Classifier. Used for the model evaluations.

'y_test.npy' is what the actual labels are for the testing part of our training data. Used ofr the model evaluations.
