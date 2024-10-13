# 🌸 Iris Dataset Linear Regression

## 🎯 Project Overview

This project implements a simple linear regression model to predict the petal length of Iris flowers based on their sepal length. Using the famous Iris dataset, we explore the relationship between these two features and build a predictive model.

### 🌟 Key Features

- Data loading and preprocessing of the Iris dataset
- Implementation of simple linear regression
- Model evaluation and prediction
- Visualization of actual vs. predicted values



## 📈 Project Steps

1. **Data Loading and Exploration**
   - Import necessary libraries: pandas, train_test_split, LinearRegression, matplotlib.pyplot, and load_iris
   - Load the Iris dataset using Scikit-learn
   - Convert the dataset into a Pandas DataFrame
   - Display the first five rows of the dataset

2. **Data Preparation**
   - Choose 'sepal length (cm)' as the feature (X) and 'petal length (cm)' as the target variable (y)
   - Split the data into training (80%) and testing (20%) sets using a random state of 42 for reproducibility

3. **Model Training**
   - Create a LinearRegression model
   - Train the model using the training data

4. **Prediction and Evaluation**
   - Use the trained model to make predictions on the test set

5. **Data Visualization**
   - Create a scatter plot of the actual values vs. the predicted values
   - Draw the regression line on the same plot to visualize the model's fit
   - Label the x-axis as 'Sepal Length (cm)' and the y-axis as 'Petal Length (cm)'
   - Include a legend for clarity

## 📊 Results

- The project demonstrates the relationship between sepal length and petal length in Iris flowers.
- The linear regression model provides insights into how well sepal length can predict petal length.
- The scatter plot with the regression line visualizes the model's performance and fit.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 📌 Future Improvements

- Implement multiple linear regression using additional features
- Explore non-linear relationships between features
- Compare performance with other machine learning algorithms
- Implement cross-validation for more robust model evaluation
