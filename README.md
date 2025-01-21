## Heart Disease Prediction using Logistic Regression

This project demonstrates the use of Logistic Regression to predict the likelihood of heart disease based on various medical features. The goal is to classify individuals as either having heart disease (1) or not having heart disease (0) based on input medical data.

### Project Overview

In this project, we use a dataset containing information about individuals’ medical conditions to predict whether they have heart disease. The dataset includes features such as age, sex, blood pressure, cholesterol levels, and more. We build a Logistic Regression model, train it on the data, and evaluate its performance using accuracy. Finally, the trained model is used to make predictions on new data.

### Steps Involved:

1. **Data Exploration**:
   - The dataset is loaded and explored. The dataset's size, structure, and basic statistics are inspected.
   - Missing values are checked, and summary statistics are displayed to understand the distribution of features.
   - The target variable (`target`) is analyzed, which indicates whether a person has heart disease (1) or not (0).

2. **Feature Selection**:
   - The target variable (`target`) is separated from the features. The features (`X`) consist of all the columns except `target`, and the target variable (`Y`) is the `target` column.

3. **Splitting the Data**:
   - The dataset is split into training and testing sets using `train_test_split`. Stratified splitting is applied to maintain the balance between classes (i.e., heart disease vs no heart disease) in both training and testing sets.

4. **Modeling with Logistic Regression**:
   - A Logistic Regression model is instantiated and trained using the training data.
   - The model is then used to predict the target variable on both the training and testing data.

5. **Model Evaluation**:
   - The model’s performance is evaluated using accuracy scores on both the training and testing datasets. Accuracy is computed by comparing the predicted values with the actual values.

6. **Making Predictions**:
   - The trained model is used to make predictions on new input data. An example input (e.g., a 62-year-old male with certain medical conditions) is provided to predict whether the person has heart disease or not.

