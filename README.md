# SUV-car-Data-Analysis
Exploratory data analysis and logistic regression modeling on the SUV purchasing dataset to predict whether a customer will purchase an SUV based on their age and estimated salary.
The analysis begins by importing necessary libraries and loading the SUV purchasing dataset. Initial exploration involves displaying the first few rows of the dataset to understand its structure. Features relevant to the prediction task, namely age and estimated salary, are selected for analysis. The dataset is split into features (X) and target variable (y) for modeling purposes.

Further preprocessing includes splitting the dataset into training and testing sets using the train_test_split function from sklearn. Additionally, feature scaling is applied using StandardScaler to standardize the features for better model performance.

Logistic regression is chosen as the predictive model due to its suitability for binary classification tasks. The model is trained on the scaled training data and then used to predict the target variable on the scaled test data. Model performance is evaluated using accuracy_score to assess the percentage of correct predictions made by the model on the test set.
