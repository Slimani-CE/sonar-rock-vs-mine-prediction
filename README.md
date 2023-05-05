# Sonar Data Classification using Logistic Regression

This is a machine learning project that classifies sonar data into two categories using Logistic Regression.

## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

## Dataset

The dataset used in this project is the Sonar dataset. It contains observations of sonar signals bouncing off a metal cylinder or a roughly cylindrical rock.

## Data Preprocessing

The dataset is preprocessed as follows:

- All columns are displayed using the `pd.options.display.max_columns` option.
- The number of rows and columns in the dataset is displayed using the `shape` method.
- A brief statistical summary of the dataset is displayed using the `describe` method.
- The count of each target value is displayed using the `value_counts` method.
- The mean of each feature by target value is displayed using the `groupby` method.
- The features and target variable are separated into X and y variables.
- The dataset is split into training and test datasets using the `train_test_split` method.

## Model Training and Evaluation

The Logistic Regression algorithm is used to train the model on the training dataset, and the accuracy of the model is evaluated on the test dataset.

The final accuracy scores achieved on the training and test datasets are displayed.

## Contributing
Contributions are always welcome! If you find any issues with the code or have suggestions for improvements, please feel free to submit a pull request.

Just remember, we are not responsible for any broken keyboards or late night coding sessions that may result from your contributions! 😄

## Show Your Support
If you found this notebook helpful, please give it a ⭐️ to show your support!
