# MachineLearning

<h1>Breast cancer prediction using SVM</h1>
What are we trying to solve?
Using patients diagnosis data (here it is data.csv) we are trying to predict whether a patient has cancer or not.

For predicting whether a patient has cancer or not we must separate out the attributes from the dataset into predictors and target. Additionally, we will also drop the attributes/columns which we will not be useful for predicting the target value.

What is the target attribute in this dataset?
'diagnosis' column which holds the value M/B is the target attribute because our aim is to predict whether a patient has cancer or not given the symptoms.

What are the predictors in this dataset?
All attributes in this dataset except 'id', 'diagnosis' are predictors. Let's see the usefulness of these predictors in further data analysis steps like - PCA, dimensionality reduction.
