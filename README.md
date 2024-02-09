# Tennis-Sport-Victory-Prediction

This project involves the following steps:

1. Data Source: Kaggle
2. Importing the required packages.
3. Uploading the CSV and log files to Databricks.
4. Reading the data file and conducting basic Exploratory Data Analysis (EDA). This includes checking column correlations and removing          highly correlated features to reduce algorithm complexity and minimize errors.
5. Selecting a subset of columns for classification purposes.
6. Cleaning the data by filtering out null values.
7. Visualizing the data for analysis.
8. Dividing the data into a training and testing set with a ratio of 60:40.
9. Establishing a pipeline for data processing and stabilising one with Logistic Regression.
10. Optimizing the learning algorithm by tuning hyperparameters using ParamGrid and CrossValidator. This involves comparing and selecting 
    the best model for the dataset.
11. Fitting the model with the training data to assess generalization to similar data.
12. Applying the classification model to the test data for evaluation.
