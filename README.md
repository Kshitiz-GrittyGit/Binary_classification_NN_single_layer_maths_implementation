**Project Overview:** To implement single hidden layer Neural network without use of any framework (i.e. TensorFlow or Pytorch) and only based on Mathematics (linear Algebra and Calculas). Comparing the result to simple logistic regression.
**Dataset :** Dataset I have downloaded from Kaggle of spaceship Titanic as I don't have GPU capability to read and execute NN's on huge datasets. It has total 8693 rows and 14 columns.
After some EDA I have created a scikit learn preprocessing pipeline.
I have used Accuracy as the performance metrics as data is balanced with equal number of positive and negative cases.
**Result:**
Logistic Regresion Accuracy ~ 77%
Single Hidden Layered Neural Network Accuracy ~79%
**Caveats:**
There don't seems a lot of difference but please note that it was just a single hidden layered NN which is roughly equivalent to Logoistic Regression.
There is also no Hyperparameter Tuning.
