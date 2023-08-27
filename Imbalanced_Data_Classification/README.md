## About

This tutorial demonstrates how to classify a highly imbalanced dataset in which the number of examples in one class greatly outnumbers the examples in another. We will work with the [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset hosted on Kaggle. The aim is to detect a mere 492 fraudulent transactions from 284,807 transactions in total. 

We will use [Keras](https://www.tensorflow.org/guide/keras/overview) to define the model and [class weights](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf/keras/Model) to help the model learn from the imbalanced data.

We will also oversample the data using both numpy and tf.data and then train the model on oversampled data and compare the results among baseline, class weights and oversampled data.


### Acknowledgment

Advanced Tutorial under [structured data](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data).