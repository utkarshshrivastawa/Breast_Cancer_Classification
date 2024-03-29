# Breast_Cancer_Classification
## Data Collection and Processing:
1. The breast cancer dataset is loaded from the sklearn library.
2. A pandas DataFrame is created with the dataset's features, and the target column ('label') is appended to this DataFrame.
3. Preliminary data exploration is conducted, including examining the first and last few rows, checking the dataset's shape, ensuring no missing values, and reviewing statistical measures of the dataset.
4. The dataset consists of 569 instances, each with 30 features and a binary target variable indicating whether the cancer is benign (1) or malignant (0).
## Data Analysis:
1. The distribution of the target variable is checked, revealing a higher number of benign cases in the dataset.
2. The mean values of the features are compared between benign and malignant cases, showing notable differences in feature values based on the cancer's diagnosis.
## Feature and Target Variable Separation:
1. Features and the target variable are separated into X (features) and Y (target) variables, respectively.
## Splitting the Data:
The dataset is split into training (80%) and testing (20%) sets using the train_test_split method from sklearn.
## Model Training:
A logistic regression model is instantiated and trained on the training dataset.
## Model Evaluation:
The model's accuracy is evaluated on both the training and testing datasets, achieving an accuracy of approximately 94.9% on the training data and 92.9% on the testing data.
## Building a Predictive System:
An example input is provided to make a prediction using the trained logistic regression model. The model predicts the cancer as benign for the given input data.

This logistic regression model serves as a basic approach to classifying breast cancer cases as benign or malignant based on features derived from digital images of breast masses. Further improvements could include feature scaling, model parameter tuning, and exploring more complex machine learning algorithms for potentially better performance.
## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
