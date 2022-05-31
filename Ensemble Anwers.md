### Final Questions (Ensemble models)

1. Which model had the best balanced accuracy score?

    The Easy Ensemble Classifier model had the best balanced accuracy score.

   |Model| Balanced accuracy score|
   |:---:|:----------------------:|
   |Balanced Random Forest Classifier (BRFC)|0.8093315767633182|
   |Easy Ensemble Classifier (EEC)|0.8411190479068211|


2. Which model had the best recall score?

    The Easy Ensemble Classifier model had higher recall scores for both the high- and low-risk loan classifications.

   |Model|Risk|Recall score|
   |:---:|:--:|-----------:|
   |BRFC|High|0.70|
   ||Low|0.92|
   |EEC|High|0.74|
   ||Low|0.95|
   
3. Which model had the best geometric mean score?

    The Easy Ensemble Classifier model had higher geometric mean scores for both the high- and low-risk loan classifications.

   |Model|Risk|Geometric mean score|
   |:---:|:--:|-----------:|
   |BRFC|High|0.80|
   ||Low|0.80|
   |EEC|High|0.83|
   ||Low|0.83|

4. What are the top three features?

    Top three features:
    
    |Rank|Feature|Score|
    |:--:|:-----:|:---:|
    |1|total_rec_prncp|0.068|
    |2|total_rec_int|0.065|
    |3|total_pymnt_inv|0.061|
    
