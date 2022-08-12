# Yelp Sentiment Classification by LSTM

This project explored the efficacy of LSTM neural networks in comparison to more standard machine learning techniques (eg random forest, logistic regression) and state of the art models (google's BERT) when classifying sentiment from text.

### Data Scope

Data set of reviews taken from the Yelp Open Dataset, specifically for reviews for New Orleans restaurants. The target variable is Yelp star rating, from 1-5.

### Tech used
* Python (pandas, Keras, tenserflow, transformers)
* R (tidyverse, ranger)
* Jupyter

### Relevant files

* Data_Explore.ipynb -- initial review filtering and train/test split
* LSTM_Build.ipynb -- review text processing + embedding, LSTM tuning and predictions
* Pretrained BERT.ipynb -- BERT tokenization, embedding, and predictions
* Test_preds/ -- folder of test set predictions for all final model designs
