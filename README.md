# 10-model-tuning-ensembling-first-n-automatically
Predicts survival probabilities of the passengers through model tuning and ensembling. You just need to input how many models you want to ensemble out of 10 classificiation models given below. It ensembles the best n models according to their cross validation accuracies for the validation set and gives n submission files (ensembled from 1 to n models) for the survival probabilities by using the tuned and ensembled models.
 
1 - LogisticRegression

2 - GaussianNB

3 - KNN

4 - SVC

5 - DecisionTree

6 - Random_Forest

7 - GBM

8 - XGBoost

9 - Artifical Neural Network (MLP)

10- CatBoost
