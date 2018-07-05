# Fingerprint to Zone Classification

## Used libraries

* pandas
* numpy
* matplotlib
* sklearn
* keras with tensorflow backend

## Steps

* loading data from csv
* shuffle data
* as input data has dictionary of features, we need to transform it to feature columns
* scaling features to (0,1)
* as its multi-class classification problem, we need to use one-hot encoding to transform labels
* splitting data into train, validation and test data sets
* defining and training simple NN with 1 hidden layer of 10 neurons using keras
* defining and training 2 more NN (one with neurons in hidden layer and one with more layers)
* comparing performance of all 3 models
* providing results, and showing predictions of the best model
