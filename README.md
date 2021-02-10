# Comparison of Classification Algorithms

In this analysis, several classification models were tested to predict whether or not a patient has cardiovascular disease.  The dataset contains 70,000 records with 12 variables, the target variable being "cardio".

The following models were built and evaluated:

1. KNN

2. Logistic Regression

3. Decision Tree

4. Random Forest

5. XGBoost

After some brief data prep, the data was partitioned to train and a test sets.  The models were built on the train data and evaluated on the test data.  The XGBoost model had the highest accuracy of all models.

<img width="225" alt="Screen Shot 2021-02-09 at 5 15 06 PM" src="https://user-images.githubusercontent.com/56644186/107436876-24678900-6afc-11eb-96db-0f6c0510a4d3.png">

The XGBoost model also had the highest AUC score of all models.

<img width="522" alt="Screen Shot 2021-02-09 at 5 15 21 PM" src="https://user-images.githubusercontent.com/56644186/107438235-2df1f080-6afe-11eb-9d49-1261d7e9c682.png">
