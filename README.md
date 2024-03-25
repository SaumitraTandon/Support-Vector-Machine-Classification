# Support Vector Machine (SVM)

This repository contains code for implementing Support Vector Machine (SVM) on a dataset of customer information for a social network ad. The code is written in Python and uses the scikit-learn library.

## Code Explanation

The code performs the following steps:

1. Imports the required libraries: numpy, matplotlib, and pandas.
2. Reads the dataset from a CSV file named `Social_Network_Ads.csv`.
3. Separates the independent variables (age and estimated salary) and the dependent variable (whether the customer purchased the product or not).
4. Splits the dataset into training and test sets.
5. Performs feature scaling on the training and test sets using the StandardScaler from scikit-learn.
6. Trains an SVM model on the training set using the SVC class from scikit-learn. The kernel is set to 'linear', and the `random_state` parameter is set to 0 for reproducibility.
7. Demonstrates how to predict a new result using the trained SVM model for an age of 30 and an estimated salary of 87,000.
8. Predicts the results for the test set.
9. Calculates the confusion matrix and accuracy score for the test set predictions.
10. Visualizes the training set results using a scatter plot and a decision boundary.
11. Visualizes the test set results using a scatter plot and a decision boundary.

## Dataset

The dataset used in this code is included in the repository and named `Social_Network_Ads.csv`. It contains the following columns:

| Age | Estimated Salary | Purchased |
| --- | ----------------- | --------- |
| 19  | 19000            | 0         |
| 35  | 20000            | 0         |
| ...  | ...               | ...       |
| 60  | 83000            | 1         |
| 39  | 73000            | 0         |

The `Age` and `Estimated Salary` columns represent the independent variables, and the `Purchased` column represents the dependent variable, indicating whether the customer purchased the product or not (0 for no, 1 for yes).

## Usage

To run the code, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:
After installing the required libraries, you can run the code by executing the Python script.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
