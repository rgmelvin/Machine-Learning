# Final Questions (Reseampling)

1. Which model had the best balanced accuracy score?

    The oversampling methods of Niave Random Oversampling and SMOTE Oversampling had highest ballanced accuracy scores. The better performance of these two methods, however, is miniscule since they differ from the undersampling methods only by a difference of 0.001. In my estimation the sampling methods were better than simple logistic regression but did not differ from each other. This makes one wonder if the slight improvement in the Balanced Accuracy Score (BAS) was due to  the relationship being non-linear or due to overfitting of the sampling methods. It makes me wonder whether these techniques are only to be used in validation studies, i.e. in the case where you are saying "what if I had a balanced data set?". And, the analysis should be performed on the unbalanced data set only.
    However, there is a fair amount of test data so these estimates are likely to be quite accurate.
    How much data is enough? I would be interested in seeing how the BAS changes with the sizes of training and test data sets for each of the methods. Then, maybe an informed choice of method could be made.

  |Model                     | Balanced Accuracy Score|
  |:------------------------:|:----------------------:|
  |Simple Logistic Regression (SLR)|0.98928|
  |Naive Random Oversampling (NRO)|0.99464|
  |SMOTE Oversampling|0.99464|
  |Cluster Cenroid Undersampling (CC)|0.99328|
  |SMOTEENN Combination Sampling|0.99328|

2. Which model had the best recall score?

    Question should be: Which *models* had the best recall score?  The oversampling models had highest recall score (see table below). Again, I am not sure if you would really care that your true positive rate is 1.00 vs. 0.99 and the result may indicate that the oversampling methods are creating a bias.

    |Model|Risk|Recall Score|
    |:---:|:-:|:----------:|
    |SLR|High|0.98|
    ||Low|0.99|
    |NRO|High|1.00|
    ||Low|0.99|
    |SMOTE|High|1.00|
    ||Low|0.99|
    |CC|High|0.99|
    ||Low|0.99|
    |SMOTEENN|High|0.99|
    ||Low|0.99|

3. Which model had the best geometric mean score?

    All of the models had the same geometric mean score.
    |Model|Risk|Geometric Mean Score|
    |:---:|:-:|:----------:|
    |SLR|High|0.99|
    ||Low|0.99|
    |NRO|High|0.99|
    ||Low|0.99|
    |SMOTE|High|0.99|
    ||Low|0.99|
    |CC|High|0.99|
    ||Low|0.99|
    |SMOTEENN|High|0.99|
    ||Low|0.99|
