# Credit-card-Fraud-Detection

# Data Set
You can download the dataset with this <a href="https://www.kaggle.com/mlg-ulb/creditcardfraud">link<\a>

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Objective
To built a model that can classify whether a transaction can be fraud or normal.

# Libraries
1. Numpy
2. Pandas
3. pyplot
4. seaborn
5. sklearn
6. imblearn

# Plots Used
1. Line plot
2. heat map
3. confusion matrix

# Step-by-step Approch
1. Importing the dataset
2. EDA of the dataset
3. Visualization.
  * To find how much data is skewed or imblanced.
4. Balancing the dataset
5. Using various algorithm to find the best working model
  Models used
  * Logistic Regression
  * Decision tree classifier
  * Random forest classifier
  * Isolation forest
6. Evaluating model accuracy based on precision and recall score, with accuracy score.
7. Using the best working model for the final evaluation.
8. Identifying the feature importance and ploting.

<img src ="https://user-images.githubusercontent.com/78545675/146034281-eceedbfb-f66f-4b09-964f-c49962d6f780.png">
