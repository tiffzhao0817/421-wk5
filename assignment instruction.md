[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/wt427A32)
# 407-week5-lab-data-preparation

Finishing lectures on data preparation.  Focusing on encoding features and dealing with outliers.

# Assignment

Use the provided dataset `synthetic_data_training.csv` to build a binary classifier (i.e., logistic regression or an SGDClassifier) that predicts the `has_disease` column. Make sure to:

- Carefully handle the missing data by choosing suitable imputation methods for both categorical and numeric columns. 
- Check for outliers
- Standardize numeric features
- Encode categorical features appropriately before training.
- Make sure to build imputation models / scaling on the training set only.

Your aim is to maximize your f1 scores!  To do this, you might try:

- Removing columns that you don't think are necessary
- Attempting different imputation methods
- Creating new features (note - we haven't done this yet, but you can inspect the data to create "meta-features" that combine existing features)
- Try a different classifier (anything in SciKit learn is fair game)

When you are done, run your best classifier on `synthetic_data_test.csv` and save a file called `answers.csv`. Report overall f1-scores for both complete cases and imputed data. Commit your notebook with your predictions for the test set.  I'll reveal your performance next week!

# Evaluation

I will evaluate your assignment based on three factors:

- Did you process your data correctly (e.g., imputing values, removing outliers, standardizing features, encoding features, while avoiding data-leakage) - 10 points
- How much effrot did you put into improving your f1 scores? Did you take a sensible approach? - 5 points
- Is your notebook clean and well-documented? - 5 points
- Did you achieve an f1-score on complete cases in the test set of at least 80%? - 5 points
- **Extra Credit** For every 5% over 80% on your complete cases, you will get an additional 1 point on the assignment.  


