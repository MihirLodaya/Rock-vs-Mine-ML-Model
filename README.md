# Rock-vs-Mine-ML-Model

Sonar Data Classification using Logistic Regression
This project focuses on classifying underwater objects as either rocks or mines using sonar data. It employs logistic regression as the classification algorithm.

Project Structure
  Importing Dependencies: This section imports the necessary libraries such as NumPy, pandas, and scikit-learn modules for data processing, modeling, and evaluation.

  Data Collection and Preprocessing: In this section, the dataset is loaded using pandas. The dataset contains sonar readings along with their corresponding labels (R for rock, M for mine). Statistical analysis and exploration of the dataset are performed to understand its structure.

  Separating the Data and Labels: The dataset is divided into features (X) and labels (Y), essential for supervised learning.

  Training and Test Data Split: The dataset is split into training and testing sets using scikit-learn's train_test_split function.

  Model Training: A logistic regression model is trained on the training data.

  Model Evaluation: The trained model's accuracy is evaluated on both training and testing datasets.

  Making Predictions: A sample predictive system is created to demonstrate how the trained model can classify new instances.

Files Included
sonar_data.csv: Dataset containing sonar readings and labels.

Conclusion
The logistic regression model achieved an accuracy of approximately 83.42% on the training data and 76.19% on the testing data, indicating its effectiveness in classifying underwater objects based on sonar readings.







