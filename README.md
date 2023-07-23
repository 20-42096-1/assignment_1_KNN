**Discussion:**The dataset was separated into training and testing sets for each cross-validation fold. The KNN classifiers were evaluated using the testing data for each fold after being trained on the training data.The precision of the classifiers trained on Manhattan and Euclidean distances was measured for each fold. The percentage of instances that were correctly categorised within the testing set is known as accuracy.

The results are as follows for each fold:

Fold 1: Manhattan accuracy is 30.54%, while Euclidean accuracy is 27.95%
Fold 2: Euclidean accuracy is 28.12%, whereas Manhattan accuracy is 30.60%.
Fold 3: Manhattan accuracy is 30.09%, and Euclidean accuracy is 27.81%
Fold 4: Euclidean accuracy is 27.73%, whereas Manhattan accuracy is 29.65%.
Fold 5: Manhattan accuracy is 30.71%, while Euclidean accuracy is 28.33%

The accuracy scores fluctuate slightly from fold to fold, demonstrating that the performance of the classifiers can change depending on how the training and testing data are separated. We compute the mean accuracy of the Manhattan (L1) and Euclidean (L2) distance metrics throughout all 5 folds. The average of the following values, given as X%: 30.54%, 30.60%, 30.09%, 29.65%, and 30.71%, is used to determine mean accuracy (Manhattan). Similar to Mean Accuracy (Euclidean), Mean Accuracy (Y%) is the average of 27.95%, 28.12%, 27.81%, 27.73%, and 28.33%. In this classification assignment, the distance metric with the higher mean accuracy is thought to perform better. The statistical significance of detected disparities can be ascertained by further investigation, and the effects of class imbalances can be evaluated.A complete picture of the classifiers' performance may be obtained by looking at per-class accuracy and other evaluation criteria.
