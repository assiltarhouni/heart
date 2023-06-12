# heart

This repository contains a Python script for data analysis and predictive modeling. The script performs the following tasks:

1. Reads a dataset from a CSV file.
2. Checks the shape of the data (number of rows and columns).
3. Identifies and counts missing values in the dataset.
4. Removes rows with missing values.
5. Checks the shape of the data after removing missing values.
6. Displays the first few rows of the dataset.
7. Provides information about the dataset.
8. Calculates descriptive statistics of the dataset.
9. Generates histograms for each column in the dataset.
10. Splits the data into a training set and a test set.
11. Defines a function to split the data into train and test sets based on a given test ratio.
12. Uses the function to split the data into train and test sets.
13. Checks if an instance belongs to the test set based on a test ratio.
14. Defines a function to split the data into train and test sets using an identifier column.
15. Uses the function to split the data into train and test sets based on an identifier column.
16. Splits the data into train and test sets using the `train_test_split` function from the `sklearn.model_selection` module.
17. Creates a new categorical feature based on the values of an existing feature.
18. Displays a histogram of the new categorical feature.
19. Performs a stratified split of the data into train and test sets based on the new categorical feature.
20. Drops the new categorical feature from the train and test sets.
21. Creates a scatter plot of two features from the train set.
22. Creates a scatter matrix of selected features in the dataset.
23. Creates a scatter plot of a feature and the target variable.
24. Splits the data into train and test sets using the `train_test_split` function from the `sklearn.model_selection` module.
25. Trains a logistic regression model on the train set.
26. Makes a prediction using the trained model.
27. Evaluates the accuracy of the model on the test set.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/assiltarhouni/heart
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repository
   ```

3. Install the required packages (if not already installed):

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

4. Place your dataset in the project directory and update the file name in the script:

   ```python
   data = pd.read_csv('dataset.csv')
   ```

5. Run the script:

   ```bash
   python coeur.py
   ```
